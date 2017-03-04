# rtl8811au driver for recent version of ubuntu

This repo contains a driver originally called `rtl8821AU_linux_v4.3.14_13455.20150212_BTCOEX20150128-51` with additional patches to get it to build on Ubuntu xenial 16.04.

I originally got the source code off a cd that came with [this usb wifi adapter](https://www.amazon.com/Heiyo-Network-600Mbps-802-11ac-Wireless/dp/B01N2NJFPG).

I tested on Ubuntu 16.04.2 LTS with kernel 4.4.0-64-generic using a "Heiyo Network Wi-Fi Dongle 802.11ac"


## Building

```
sudo make clean
make -j 8
sudo make install
```

## License
The driver license appears to be GPLv2
