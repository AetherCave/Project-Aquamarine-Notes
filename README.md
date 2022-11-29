# Project-Aquamarine-Notes

## Closed Alpha v0.01 (Halium Boot)

- Solved some errors during building process
- Updating the files from device tree
- Updating and patching kernel
- Not built yet, not tested

### Common errors during process:

- Not finding the `devices` directory: 
In the guide, you have to create a manifest for your device in the directory `devices`, which is not on the root of your `BUILDDIR`

The directory is located in `halium/halium/devices/manifests/`

- The given device is not supported: this is a very common error, and it's because you put your manifest in the wrong directory.

- `#include openssl/opensslv.h : file does not exist`:
Install `openssl` on your distro.
