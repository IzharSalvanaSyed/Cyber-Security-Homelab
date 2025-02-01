# Cyber-Security-Homelab __ Need to update

### Table of contents

1. [Introduction](#introduction)
2. [Hardware](#hardware)
3. [Plan](#plan)
4. [Installing Proxmox](#proxmox)
5. [palcehodler](#assessment)
6. [placeholder](#summary)

## Introduction <a name="introduction">
I will give step-by-step instructions in this lab, as documentation is always good for traceability. This lab aims to gain experience in VMs, networking, firewalls, routing, Active Directory, Kali Linux, and other blue team tools. 

## Creating a home lab
A home lab depends on what you want to do with it, which can range from creating a whole test environment, test app development, and or running monitoring programs such as SIEMS, IDRs, and or EDRs. What you ultimately do is up to you. The Type of hardware to help house your home lab can range from very expensive to affordable, or even old computer hardware that you can repurpose. Using old computer hardware or running a type 2 hypervisor such as VMware or Virtual Box are two options you can choose from. I purchased old computer hardware to run a type 1 hypervisor such as Proxmox or EXSI. I chose to go with Proxmox as I have a few friends and family members who are experienced with it, and they would come in handy if I needed to ask questions.  I have experience running a NAS and virtualizing from building and running my Unraid Server. However, Proxmox is similar but also very different. I am still gaining experience in cybersecurity, networking, and the broad scope of IT. I, however, had a little experience here and there and have some transferable skills. The home lab will be a work in progress, but at the same time, it will be a learning experience in many ways. With that out of the way, I had a lot of fun, with many frustrations, creating my home lab. 

## Hardware <a name="hardware">
- HP Prodesk 600 G5 MT
  - CPU: Intel Core I5-9500
      - 6 cores and 6 threads
  - Memory: 32 GB of mixed ram
      - it came with 16 GB, and I had another 16 GB lying around
  - Storage:
    - 1 TB NVME

What you choose for your hardware is your choice, and by no means do you need as much storage or RAM as I put in, as I just had them lying around and needed to find some purpose for them.


## Plan <a name="plan">



## Installing Proxmox <a name="proxmox">

### Creating an installation USB for Proxmox  
1. Download Proxmox ISO from the [proxmox website](https://www.proxmox.com/en/downloads/proxmox-virtual-environment/iso)
2. Create a bootable Proxmox Installation USB
   - There are many ways to create a bootable USB Stick, but I used Balena Etcher.
     1. Download [BalenaEtcher](https://etcher.balena.io/)
     2. Install BalenaEtcher
     3. Plug in a USB Stick
     4. Open BalenaEtcher
     5. Select Proxmox ISO image
     6. Select the USB stick to Flash Proxmox ISO
     7. Wait a while for it to flash
     8. FINISH
    
### Instal Proxmox  
1. Plug the USB to an available USB port on your Computer
2. Press Delete, F2, or whatever key you need to press to get into the Bios
3. Change the boot order to start up with the Flashed USB

### Installation Process
- you can use this guide to [install Proxmox](https://pve.proxmox.com/wiki/Installation)
- Followed this video at [9:39](https://youtu.be/gTCZ-g-cbbE?t=138) to install Proxmox

