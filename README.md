# alienvault-pfsense
PFsense plugin for AlienVault USM

This is a plugin for AlienVault USM and logs from the pfsense firewall (http://www.pfsense.org/).
Log format is explained here: https://doc.pfsense.org/index.php/Filter_Log_Format_for_pfSense_2.2


Usage:

Copy the pfsense.cfg to /etc/ossim/agent/plugins and activate as usual.

This plugin shares the Plugin ID and SID with the pf packetfilter plugin (plugin id 1560).

The plugin rules have also been integrated into the official AlienVault USM5 OpenBSD/pf plugin starting from December 2015.

