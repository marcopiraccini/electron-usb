# electron-usb
node-usb fork to be used with electron. It's a fork from node-usb which binary are released on github.
It's a temporary solution until binary package will be available for node 5.1.x and
windows / linux platforms on node-usb. Pleas refer to https://github.com/nonolith/node-usb on
how to use these APIs.

# Prerequisite
Install the node version used by electron (currently is 5.1.1 for electron 0.36.7).

# Linux build

On Ubuntu 15.10, install:
```
sudo apt-get install libudev-dev libusb-1.0-0-dev g++-multilib libudev-dev:i386
```
And then run `npm run release` (x64) or `npm run release-ia32` (ia32) to publish
the binary build

# Windows build

Use a  Windows 7 on x64. Install Visual Studio 2013 and Python
Run `npm run release --msvs_version=2013` (x64) or `npm run release-ia32 --msvs_version=2013` (ia32)

# OSx build
[TODO]
