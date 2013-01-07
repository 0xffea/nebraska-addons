include /usr/share/cibs/rules/ips.mk
include /usr/share/cibs/rules/archive.mk
include /usr/share/cibs/rules/autotools.mk
include /usr/share/cibs/rules/64.mk

summary := PostgreSQL is a powerful, open source object-relational database system.
license := BSD
license-file := COPYRIGHT

configure-options += \
	--enable-dtrace \
	--with-python \

name     := postgresql
home     := http://www.postgresql.org/
version  := 9.2.2
archive  := $(name)-$(version).tar.bz2
download := http://ftp.postgresql.org/pub/source/v$(version)/$(archive)
checksum := \
	sha1:edadf238bcf51bd6e92dfe2f8afb3665510297a6
