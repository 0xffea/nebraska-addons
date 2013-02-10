include /usr/share/cibs/rules/ips.mk
include /usr/share/cibs/rules/archive.mk
include /usr/share/cibs/rules/autotools.mk
include /usr/share/cibs/rules/64.mk

summary := Multi-format archive and compression library.
license := MIT
license-file := COPYING

# -llzma missing from linker options
configure-options +=		\
	--without-lzmadec	\
	--without-lzma		\

name	 := libarchive
home	 := http://www.libarchive.org/
version	 := 3.1.2
archive	 := $(name)-$(version).tar.gz
download := http://www.libarchive.org/downloads/$(archive)
checksum := \
	sha1:6a991777ecb0f890be931cec4aec856d1a195489
