# Home-IT-lab
Documented personal IT and cybersecurity home lab focused on Windows, Linux, networking, and troubleshooting fundamentals.
## Overview
Built a personal IT lab using VirtualBox with Windows 10 and Ubuntu Linux.

## Tools Used
- VirtualBox
- Windows 10
- Ubuntu 22.04

## What I Practiced
- Creating and managing user accounts
- Admin vs standard permissions
- VM snapshots
- Basic networking (IP, DNS, gateway)
- Linux file system and permissions

## Issues I Ran Into
- Missconfigured snapshot led to deletion of sudo user
- unable to reach destinaiton host while pinging 

## How I Fixed Them
- launched unbunto in advanced mode (shift + esc while launching) and assigned sudo persmisions to new local user 
- Switched from NAT mode to Bridged Adaptor mode (Could have also created a NAT Network but oppted for BA)

## What I Learned
- Doubble check your snapshot saved correctly to ensure intentional restorations 
- Make sure your networks corespond and also ensure your on Bridged or NAT Network mode so you can ping other systems (Set your promiscuous mode to allow all)
