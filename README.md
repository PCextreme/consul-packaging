# System packages for Consul
[Consul](http://consul.io/) is a tool which has multiple components like
service discovery, a key-value store and health checking.

Consul is only available in a .zip which distributes the pre-compiled binary
of Consul.

This repository contains the scripts to create Debian/Ubuntu packages so that
Consul is easy to set up.

## Build packages
Make sure you have these dependencies installed:
* dpkg-dev
* curl
* unzip

You can then build the package easily:

``$ dpkg-buildpackage``

This should give you a .deb package ready for installation!

## Supported distributions
This was tested on Ubuntu 14.04 with Upstart. Support for Ubuntu 16.04 will be
added at a later point.

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
