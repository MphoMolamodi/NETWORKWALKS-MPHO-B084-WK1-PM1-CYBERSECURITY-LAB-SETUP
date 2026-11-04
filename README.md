# NETWORKWALKS-MPHO-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
This repository contains cybersecurity labs from the Networkwalks internship

## My Lab Setup
-Downloaded and installed 7-zip.

-Why?: Needed to extract Kali Vm archive.

-Downloaded and installed virtual box.

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

<img width="500" height="500" alt="Kali extracted on vm" src="https://github.com/user-attachments/assets/6553ffe9-8405-42a9-b685-30a379829bff" />

<img width="500" height="500" alt="Kali access to windows folder" src="https://github.com/user-attachments/assets/da4da24a-b085-484b-98df-f51561210fc8" />

<img width="500" height="500" alt="kali ping test" src="https://github.com/user-attachments/assets/c46851e1-2d5d-4714-a51b-3afaf7edf4d1" />

<img width="500" height="500" alt="Kali connected to vm" src="https://github.com/user-attachments/assets/411b8ef0-e4e1-4b03-ad0e-e755ba57c252" />






## Tools used 
- Web browser
- 7-zip
- qBittorrent
- Kali Linux
  



