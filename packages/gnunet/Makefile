include /usr/share/cibs/rules/ips.mk
include /usr/share/cibs/rules/archive.mk
include /usr/share/cibs/rules/autotools.mk
include /usr/share/cibs/rules/64.mk

summary := GNUnet is a framework for secure peer-to-peer networking that does not use any centralized or otherwise tr
license := GPLv3
license-file := COPYING

CFLAGS := -I/usr/include/idn

build-depends += \
	library/glib1           \
	library/libextractor    \
	library/libgcrypt       \
	library/libgtop         \
	library/libidn          \

name	 := gnunet
home	 := http://www.gnu.org/software/$(name)
version	 := 0.9.5a
archive	 := $(name)-$(version).tar.gz
download := ftp://ftp.gnu.org/gnu/$(name)/$(archive)
checksum := \
	sha1:e7f5f5e4814dd008b4e0bbc0ba4cbc6dc635b5e0
