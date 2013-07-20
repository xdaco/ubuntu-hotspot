ubuntu-hotspot
==============

This project makes a linuxbox into a wifi access point. Any existing internet connection in the box can be shared over the created access point.
The installer will automatically install hostapd, uninstall default dhcp server dhcpd and install dnsmasq. And to use it it will install a bash 
script named hotspot.


How to :

Download installer.
Download hotspot
open terminal in the downloaded folder
and type:

$ sudo chmod a+x installer

$ sudo chmod a+x hotspot

$ sudo sh ./installer
