include /usr/share/cibs/rules/ips.mk
include /usr/share/cibs/rules/archive.mk
include /usr/share/cibs/rules/autotools.mk
include /usr/share/cibs/rules/64.mk

summary := LibYAML is a YAML 1.1 parser and emitter written in C.
license := MIT
license-file := LICENSE

configure-env += \
	CFLAGS="-I/usr/gnu/include"
configure-env.64 += \
	LDFLAGS="-L/usr/gnu/lib/amd64"

configure-options += \
	--disable-perl	\
	--disable-lua

name     := weechat
home     := http://weechat.org/
version  := 0.3.9.2
archive  := $(name)-$(version).tar.gz
download := http://weechat.org/files/src/$(archive)
checksum := \
	sha1:1b9152451cb463b84cc0916b446f565d3ecde76e
