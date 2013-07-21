ubuntu-hotspot
==============

This project makes a linuxbox into a wifi access point. Any existing internet connection in the box can be shared over the created access point.
The installer will automatically install hostapd, uninstall default dhcp server dhcpd and install dnsmasq. And to use it it will install a bash 
script named hotspot.


How to:
-------

*Download the released soucrecode [from here](https://github.com/xdaco/ubuntu-hotspot/releases) and Extract.
Go to the extracted folder.
Open terminal and  type:*

#
```bash
$ sudo chmod a+x installer
$ sudo bash ./installer

````
