include /usr/share/cibs/rules/ips.mk
include /usr/share/cibs/rules/archive.mk
include /usr/share/cibs/rules/autotools.mk
include /usr/share/cibs/rules/32.mk
include /usr/share/cibs/rules/64.mk

summary := Free & open source, high-performance, distributed memory object caching system.
license := MIT
license-file := COPYING

build-depends += \
	libevent

name	 := memcached
home	 := http://memcached.org/
version	 := 1.4.15
archive	 := $(name)-$(version).tar.gz
download := http://memcached.googlecode.com/files/$(archive)
checksum := \
	sha1:12ec84011f408846250a462ab9e8e967a2e8cbbc
