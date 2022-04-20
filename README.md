# config

CONFIG includes configure files from

* Arch (CONFIG.tar)
* ArchCraft (CONFIGS.tar.gz)
* Ubuntu.openbox ()

To get a usb wlan working:
* rtl8192eu driver for linux version 5.2.19.1

### Software updates on Arch (pacman)

    sudo pacman -Sy $(pacman -Qu | awk '{printf $1" "} END{print ""}')
