nebraska-addons
===============

Add-on packages for Nebraska.

Setup a local ips server
------------------------

mkdir /var/pkgrepo

pkgrepo create /var/pkgrepo
pkgrepo set -s /var/pkgrepo publisher/prefix=nebraska

svccfg -s pkg/server setprop pkg/readonly=false

svcadm refresh pkg/server
svcadm enable pkg/server

pkgrepo info -s http://localhost
