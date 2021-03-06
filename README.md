# jetsonUtilities
This repository holds utilities for working with NVIDIA Jetson Development Kit

# jetsonInfo
Get information about the NVIDIA Jetson OS environment on NVIDIA Jetson Development Kits (TK1, TX1, TX2)

The information about the NVIDIA Jetson Development Kit operating system is spread over a few files. This is a handy tool to use for reference.

The Python script jetsoninfo.py will list the hardware, version of L4T that is running, Ubuntu version, and the Linux kernel revision. To execute:

$ python jetsonInfo.py

or

$ ./jetsonInfo.py

The hardware designator is derived from the file: '/proc/cpuinfo'

The L4T version is derived from the file: '/etc/nv_tegra_release'

The Ubuntu version is derived from the file: '/etc/os-release'

The Linux kernel version is derived from the file: '/proc/version'
