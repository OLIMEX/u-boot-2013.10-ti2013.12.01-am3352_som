# am3352-u-boot-2013.10
* Removed beagle* eeprom dependency
* Removed PMU Code /We do not use PMU at AM3352-SOM/
* Fixed DDR2 timings
* Other fixes needed by AM3352-SOM

Compile using official u-boot README
1.Compile using selected toolchain
make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- am335x_evm_config
make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- -j4

