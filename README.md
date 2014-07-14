WiFi chameleon is a script for automatically switching a wifi card from access
point mode (using hostapd) to client mode (with wpa_supplicant).

Currently it requires:

1) Working hostapd setup with dnsmasq
2) Working wpa_supplicant setup

Everything is command line based. If you have
these working on your system you should be able to simply modify
the parameters at the top of wifi-chameleon to match your
setup.
