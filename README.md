This is a fork of [David
Albrecht](https://github.com/david00)'s [Raspberry Pi Power
Monitor](https://github.com/david00/rpi-power-monitor), see [David00's
README](https://github.com/david00/rpi-power-monitor/README.md) for
information about his proect. This fork is to adapt the project to
monitoring a PV + battery storage system.

Planned changes:

* Add a new CT class, Storage.
* Measure consumption and utility usage directly instead of
  calculating them. Accordingly it will require at least one CT on the
  service entry set to the mains category and one on load feeder set
  to the consumption category.

### Credits

* [OpenEnergyMonitor](https://openenergymonitor.org) and forum member Robert.Wall for guidance and support

* The `spidev` project on PyPi for providing the interface to read an analog to digital converter
