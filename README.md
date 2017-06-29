# Archer_C7v2_Sniffer_image
Enable TP-Link C7v2 image with needed tool for Wireless Sniffer usage.
Here we use the LEDE with customized tool/driver/firmware for TP-Link Archer C7 v2.

The LEDE is branch of openwrt and also future of this famous open source project.
if you are interested in LEDE. Please refer to https://lede-project.org/ .

The current verified AP is only C7 version 2.(Version 3/4 is not tested)
With the image, you can set command on your own to enable Sinffer function.
Or you can also use my the other python project to complete all the stuff.

####################################################################
#
# HOW TO UDATE YOUR FIRMWARE
#
###################################################################

1. The official firmware (Stock firmware)
If you just take out the AP form box, you need to use factory.bin.
The factory.bin is target for stock firmware.
You just log in TP Link page(Seems 192.168.0.1), Go to update firmware page.
Then select the factory.bin such as

lede-ar71xx-generic-archer-c7-v2-squashfs-factory.bin
lede-ar71xx-generic-archer-c7-v2-squashfs-factory-eu.bin
lede-ar71xx-generic-archer-c7-v2-squashfs-factory-us.bin

Any of above
If you meet error message, try to rename above binary to be only "factory.bin"

2. Flashed openwrt/LEDE firmware
Go to System/Backup or Flash firmware page.
To flash new image section -> browse below image.

lede-ar71xx-generic-archer-c7-v2-squashfs-sysupgrade.bin

Then procee to start the whole update image flow until done.

After login to luci page, you are ready to go.

coDerOnMars
