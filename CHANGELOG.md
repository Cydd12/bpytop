# Changelog

## v1.0.13

* Fixed: Cpu usage bug when showing tree and memory in percent
* Fixed: Check for minimum terminal size at start when init screen is enabled

## v1.0.12

* Fixed: Cpu high and cpu crit for osx and raspberry pi

## v1.0.11

* Fixed: getsensors detection of vcgencmd
* Fixed: Load AVG being drawn outside box on small sizes
* Fixed: Slowdown when showing memory in percent instead of bytes
* Fixed: Cpu temperature colors not converted to percent of cpu critical temp
* Fixed: Crash on sorting change when lacking permissions

## v1.0.10

* Fixed: Raspberry pi cpu temps, actually fixed this time...

## v1.0.9

* Fixed: Raspberry pi cpu temp, again.

## v1.0.8

* Added: Set terminal title at start
* Added: Update checker, can be toggled off in options menu
* Added: Option to show memory in bytes for processes, enabled by default
* Added: Options to set custom network graphs minimum scaling values and a "auto" button to toggle manual and default values.
* Fixed: Failure to detect cpu temp on raspberry pi
* Changed: Layout changes to cpu box

## v1.0.7

* Changed: Info box now restores last selection on close
* Fixed: Crash when starting with show_disks=False

## v1.0.6

* Fixed: Cpu temps index error on uneven temp collection
* Fixed: No cpu percent in info box when filtering

## v1.0.5

* Fixed: Attribute typo in detailed process collection

## v1.0.4

* Fixed: Crash when filtering and showing info box
* Added: Improved cpu temperature detection
* Fixed: Broken cpu box layout on high core count and change to default layout
* Changed: Selection now returns to last selection when pressing down from info box

## v1.0.3

* Fixed: Crash on detailed info when showing tree
* Fixed: Incorrect sorting for memory
* FIxed: Removed unsupported osx psutil values
* Changed: Removed shift modifiers for some keys and removed redundant toggles

## v1.0.2

* Added: IndexError catch for cpu temperature collection
* Fixed: net_io_counters() not iterating over itself
* Fixed: Clear mouse queue to avoid accidental character interpretation
* Added: "/etc/bpytop.conf" as default seed for config file creation if it exists.
* Added: Error handling for exception in psutil.cpu_freq()

## v1.0.1

* Fixed: Bad assumption of cpu model name string contents.
* Added: Exception catch for psutil io_counters error caused by psutil < 5.7.0 and Linux kernel >= 5
* Added: Error handling for psutil.net_io_counters() errors.

## v1.0.0

* First release
* Missing update checker
