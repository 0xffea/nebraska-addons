include /usr/share/cibs/rules/ips.mk
include /usr/share/cibs/rules/archive.mk
include /usr/share/cibs/rules/autotools.mk
include /usr/share/cibs/rules/64.mk

summary := Libgcrypt is a general purpose cryptographic library based on the code from GnuPG.
license := GPLv2
license-file := COPYING

build-depends += \
	libgpg-error

name     := libgcrypt
home     := http://www.gnu.org/software/libgcrypt/
version  := 1.5.0
archive  := $(name)-$(version).tar.bz2
download := ftp://ftp.gnupg.org/gcrypt/$(name)/$(archive)
checksum := \
	sha1:3e776d44375dc1a710560b98ae8437d5da6e32cf
