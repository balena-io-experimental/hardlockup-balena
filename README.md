Building the out-of-tree hardlockup kernel module from https://github.com/balena-io-playground/hardlockup.

The resulting module will be located in the `hardlockup_${BALENA_DEVICE_TYPE}_${OS_VERSION}` after after build.

It can be loaded from a terminal with `insmod hardlockup.ko`. Afterwards the system will immediately freeze
and the hardware watchdog will kick in after 10 seconds.
