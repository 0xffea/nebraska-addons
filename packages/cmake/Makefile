include /usr/share/cibs/rules/ips.mk
include /usr/share/cibs/rules/archive.mk
include /usr/share/cibs/rules/autotools.mk
include /usr/share/cibs/rules/32.mk

summary := CMake is a family of tools designed to build, test and package software.
license := MIT
license-file := Copyright.txt

build-depends += \
	
configure-options =			\
	--prefix=$(prefix)		\
#	--mandir=$(prefix)/share/man	\
#	--system-libarchive		\
	--system-bzip2			\
	--system-zlib			\
	--system-curl			\

name     := cmake
home     := http://cmake.org/
version  := 2.8.10
archive  := $(name)-$(version).2.tar.gz
download := http://www.cmake.org/files/v2.8/$(archive)
checksum := \
	sha1:2d868ccc3f9f2aa7c2844bd0a4609d5313edaaec
