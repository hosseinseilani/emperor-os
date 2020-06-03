# Download Emperor-OS Linux Image

Emperor-OS is available for everyone for free, easy to use, with five desktops for laptop and desktop computers. It is a complete set of tools for programmers, developers and the field of data science in one ISO file.
This page provides the link to download Emperor Linux in its latest official release:


Emperor-OS18.0.4.4.iso
SHA256Sum

# How to create Emperor-OS Bootable USB Drive
## Create bootable USB in Windows:

Download unetbootin and run the downloaded exe file. Follow the following link that outlines the process of writing the downloaded ISO onto the USB Device:
https://unetbootin.github.io/#install

## Create bootable USB in Linux

You can download unetbootin in Linux as well to create a bootable Live USB. You can also use the dd command to create a bootable USB. The dd command usage is listed below. Please make sure that you replace /dev/sdx with the USB device name and provide appropriate path for Empror-OS's ISO file.

sudo dd if=/path/to/Emperor-OS.14.04.iso of=/dev/sdx status=progress oflag=sync bs=10M

Please make sure you pass the device name and not the partition name instead of /dev/sdx else it would not work. Device names usually end in letters like /dev/sdc or /dev/sdd and partition names end with a number like /dev/sdc1 or /dev/sdd2.

---

## The default account user and password of Emperor-OS is user.
* Username: user
* Password: user

##The password of root account of Emperor-OS is user.
* Username: root
* Password: user
