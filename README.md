# OSPF-error-detector
Script to detect OSPF mismatches

AUTHOR: IPvZero


DATE: 24rd Nov 2020


Purpose: Automated Check to check OSPF links are share the same network/mask, area and timers.


Scope: This script used CDP was designed to be used on directly links.


Switched shared segments will break the CDP logic.


Notes: This script uses Nornir2, not Nornir3. Install with:
pip3 install nornir"<3"


Tested: This script was tested using CSR1000v Images (Cisco IOS XE Software, Version 16.11.01b)
