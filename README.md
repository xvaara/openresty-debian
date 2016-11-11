# openresty-debian
Builds a deb package for OpenResty 1.11.2.1

## Notes

* All files go in the standard debian nginx locations
* Includes init, logrotate, and post/pre install/remove scripts from the official nginx package.
* Builds for Debian by default.
* LuaJIT upgraded to 2.1 Beta 2
* Includes a bundled copy of LuaRocks 2.4.1
* Statically linked against OpenSSL 1.0.2h, PCRE 8.3.9, ZLib 1.2.8

## Usage

Run ```./build``` from the project root. When it completes you'll have a deb in ```./artifacts```.

## Changelog by @nullivex
* Add build-extras to build an openresty similar to nginx-extras
* Port Dockerfile to traditional bash script as an alternate to Dockerfile build.
* Update to the latest versions with 1.11.2.1

