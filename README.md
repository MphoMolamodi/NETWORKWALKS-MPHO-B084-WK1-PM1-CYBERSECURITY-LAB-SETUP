# NETWORKWALKS-MPHO-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
This repository contains cybersecurity labs from the Networkwalks internship

## My Lab Setup
-Downloaded and installed 7-zip .
-Why?: Needed to extract Kali Vm archive.
-Downloaded and installed virtual box .
-Changed my default Machine folder to 'D:vms'.

## Virtual Machine Network configuration
-VirtualBox > Files > Tools >Network manager > NAT Networks > create
-Configuration:
-Network Name: NAT Network
-Network CIDR: 10.0.0.0/24
-Supports DCHP: Enabled
-IPv6: Disabled
-All VMs attached to this network to allow inter-communication.

## Kali Linux setup
-Downloaded Kali Linux from its official website, but the download countdown got stuck at 0kb and Kali could not install.
-Re-attempted to download the Torrent version and installed qBittorrent app to aid with extraction of Kali linux.
-Used 7-zip to extract the second folder of the Kali linux.
-Kali Debian got installed on the VirtualBox.
## Kali Debian configuration
-Opened Kali and used the command prompt "ip a" to check the current ip and changed it to 10.0.0.2/24 and connected it to the VM NAT Network.
-To test if the Kali and Vm were linked, I pinged 10.0.0.0/24 and used the ls prompt to check folder access.

## Tools used 
- Web browser
- 7-zip
- qBittorrent
- Kali Linux
  


-
-
