# platform-banana-pi
Platform files for banana-pi devices

BPI-Sinovoip sources: http://github.com/BPI-SINOVOIP/BPI-M2U-bsp

This repo contains all platform-specific files, used by the Volumio Builder to create **banana-pi** images:

- Kernel (kernel, modules, firmware)
- Other files e.g. u-boot, configuration files, uEnv.txt, bootcmd, boot.scr etc.

The BSP is used to generate most of the needed components.
A Volumio-specific script can be used to copy out the data to the platform folder and tar it.
The tar is to be used by the Volumio build process.

**Platform BSP-M2U files with kernel version 3.10.65**
- 20161129: First commit for Volumio 2

** Waiting for more documentation on bpi-m2u, currently initrd does not load **

