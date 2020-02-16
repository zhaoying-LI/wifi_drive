# Wi-Fi drive
## Install instruction:
* `make clean`
* `make`
* `sudo insmod 8192eu.ko`

## Note:

* You can check if the driver is successfully loaded by running `lsmod`
* After rebooting, the loaded diver might be deleted automtically. You need to load it again by running <br> `sudo insmod 8192eu.ko`
