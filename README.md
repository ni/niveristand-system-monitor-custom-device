# System Monitor Custom Device

**System Monitor Custom Device** is a Custom Device that tracks memory resources and CPU usage on an RT Target running the VeriStand Engine.  Set the update rate (Hz) in the System Explorer to determine how often the custom device checks the CPU usage and memory resource values and sends them to the VeriStand Engine.

The NI VeriStand System Monitor can only be used on an RT Target. Running a System Definition File targeted to localhost that contains an System Monitor Custom Device will produce an error.

## LabVIEW Version

LabVIEW 2015

## Git History & Rebasing Policy
Branch rebasing and other history modifications will be listed here, with several notable exceptions:
- Branches prefixed with `dev/` may be rebased, overwritten, or deleted at any time.
- Pull requests may be squashed on merge.

## License

The NI Synchronization Custom Device is licensed under an MIT-style license (see LICENSE). Other incorporated projects may be licensed under different licenses. All licenses allow for non-commercial and commercial use.
