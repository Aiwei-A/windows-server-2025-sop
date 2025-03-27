# Standard Operating Procedure  
MITT  
1551 Pembina Highway
Winnipeg, MB, Canada  R3T 2E5
2049711349  
Version 1.0  
Written by: Aiwei Tu  
Approved by: IT Manager  
Date: 03/26/2025  

---

## Purpose  
This document describes how to install and configure Windows Server 2025 in a corporate environment to ensure server deployment is standardized, secure, and comply with usage standards.

---

## Application  
This operation process is for corporate IT administrators and is used to deploy new Windows Server 2025 instances into intranet systems.

---

## Definitions  
- SOP： Standard Operating Procedure
- ISO： System image file
- RDP： Remote Desktop Protocol
- IP：  Network address
- DNS： Domain name resolution server

---

## Procedure Steps  

### Step 1:   Prepare the installation media
-   Download ISO image for Windows Server 2025
-     Mount the ISO file in the virtual machine

### Step 2: Install the system  
-  Start with ISO
- Select the number of CPU and core, set the memory size, select the network adapter type, the number of hard disks, and click "Install"
- Check "I don't have the key" and select the version with desktop experience.  
- Select Custom Installation, partition and start the installation.

### Step 3: Setting up initial configuration 
- Set the administrator password  


### Step 4: Configure the network  
- Set a static IP address, such as:  
- IP: 192.168.1.100  
- Subnet mask: 255.255.255.0  
- Gateway: 192.168.1.1  
- DNS: 8.8.8.8, 1.1.1.1

### Step 5: Enable Remote Desktop  
- Open System Settings → Enable Remote Desktop  
- Add firewall rules:  

---

## Resources  
- Windows Server 2025 ISO [Download address](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2025?msockid=0781d120738e6f2e07d5c52272936e8e)
- MITT IT Manual
