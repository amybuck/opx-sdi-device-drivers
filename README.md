# opx-sdi-device-drivers
This repository contains SDI device drivers for the OpenSwitch project, and creates library libopx_sdi_device_drivers so that it is loaded by the `opx-sdi-sys` repo.  

This repository contains the device drivers for various chips used on Dell hardware. The combination of the `opx-sdi-sys`, `opx-sdi-framework` and `opx-sdi-device-drivers` provides a full implementation of the `opx-sdi-api`.

## Build
See [opx-nas-manifest](https://github.com/open-switch/opx-nas-manifest) for more details on the common build tools. 

### Build dependencies

- `opx-logging`
- `opx-common-utils`
- `opx-sdi-api`
- `opx-sdi-framework`
- `opx-sdi-sys`

Dependent packages: libopx-logging1 libopx-logging-dev libopx-common1 libopx-common-dev libopx-sdi-framework1 libopx-sdi-framework-dev libopx-sdi-sys1 libopx-sdi-sys-dev opx-sdi-api-dev

(c) Dell 2017
