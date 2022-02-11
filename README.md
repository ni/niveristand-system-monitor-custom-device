# System Monitor Custom Device

The **System Monitor Custom Device** tracks memory resources and CPU usage on an RT Target running the VeriStand Engine.  Set the update rate (Hz) in the System Explorer to determine how often the custom device checks the CPU usage and memory resource values and sends them to the VeriStand Engine.

The System Monitor Custom Device can only be used on an RT Target. Deploying a System Definition File that contains an System Monitor Custom Device will produce an error when targeting a Windows system.

## LabVIEW Source Code Version

LabVIEW 2019

## Dependencies

### Running the custom device

- [VeriStand 2019 or later](https://www.ni.com/en-us/support/downloads/software-products/download.veristand.html)

### Developing or building from source

- [LabVIEW 2019 or later](https://www.ni.com/en-us/support/downloads/software-products/download.labview.html)
- [LabVIEW Real-Time Module](https://www.ni.com/en-us/support/downloads/software-products/download.labview-real-time-module.html)
- [VeriStand Custom Device Development Tools](https://github.com/ni/niveristand-custom-device-development-tools)
- [VeriStand Custom Device Testing Tools](https://github.com/ni/niveristand-custom-device-testing-tools)

## Git History & Rebasing Policy
Branch rebasing and other history modifications will be listed here, with several notable exceptions:
- Branches prefixed with `dev/` may be rebased, overwritten, or deleted at any time.
- Pull requests may be squashed on merge.

## License

The NI Synchronization Custom Device is licensed under an MIT-style license (see LICENSE). Other incorporated projects may be licensed under different licenses. All licenses allow for non-commercial and commercial use.