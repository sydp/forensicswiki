---
tags:
  -  Network Forensics
  -  Articles that need to be expanded
---
**Wireless forensics** is the process of capturing information that
moves over a wireless network and trying to make sense of it in some
kind of forensics capacity.

## Wireless Local Area Networks

*WLANs are standardized under the IEEE 802.11 series.*

Common encryption technologies used by these networks are: WEP,
WPA/WPA2-PSK, some networks have no encryption at all.

In order to decrypt intercepted secured WLAN traffic you should crack
the encryption key. Note, that the only option for cracking WPA/WPA2-PSK
keys is to do a brute-force password guessing attack. There are several
WPA-PSK [rainbow tables](rainbow_tables.md)
[available](http://www.renderlab.net/projects/WPA-tables/).

Many commercial [network forensics](network_forensics.md)
systems can intercept and decrypt WLAN traffic, for example:

- Mera Systems [NetBeholder Mobile](http://netbeholder.com/)
- E-Detective [Wireless Detective
  System](http://www.edecision4u.com/edecision4u/Products.html)
- Expert Team [3i Tactical System
  (3iTS)](http://www.expert-team.net/Products.html)

As well as some open-source tools:

- [aircrack-ng](http://aircrack-ng.org/doku.php)

WPA/WPA2-PSK cracking-only solutions with [GPU
acceleration](forensics_on_gpus.md) (15-100 times faster than in
CPU-only mode):

- [ElcomSoft Distributed Password
  Recovery](http://www.elcomsoft.com/edpr.html)
- [Pyrit](http://code.google.com/p/pyrit/)

## Wireless Metropolitan Area Networks

## GSM networks

## Other networks

