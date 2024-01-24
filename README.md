# Cyber-Security-Homelab

# Table of contents

1. [Introduction](#introduction)
2. [placeholder](#control-assessment)
3. [placeholder](#workflow)
4. [placeholder](#checklist)
5. [palcehodler](#assessment)
6. [placeholder](#summary)

# Introduction <a name="introduction">
I will try to give step-by-step instructions in this lab, as documentation is always good for traceability. This lab aims to gain experience in VMs, networking, firewalls, routing, Active Directory, Kali Linux, and other blue team tools. 

# Creating a home lab
A home lab depends on what you want to do with it, which can range from creating a whole test environment, test app development, and or running monitoring programs such as SIEMS, IDRs, and or EDRs. What you ultimately do is up to you. The Type of hardware to help house your home lab can range from very expensive to affordable, or even old computer hardware that you can repurpose. Using old computer hardware or running a type 2 hypervisor such as VMware or Virtual Box are two options you can choose from. I purchased old computer hardware to run a type 1 hypervisor such as Proxmox or EXSI. I chose to go with Proxmox as I have a few friends and family members who are experienced with it, and they would come in handy if I needed to ask questions.  I have experience running a NAS and virtualizing from building and running my Unraid Server. However, Proxmox is similar but also very different. I am still gaining experience in cybersecurity, networking, and the broad scope of IT. I, however, had a little experience here and there and have some transferable skills. The home lab will be a work in progress, but at the same time, it will be a learning experience in many ways. With that out of the way, I had a lot of fun, with many frustrations, creating my home lab. 

# Hardware
- HP Prodesk 600 G5 MT
  CPU: Intel Core I5-9500
      - 6 cores and six threads
  - Memory: 32 GB of mixed ram
      - it came with 16 GB, and I had another 16 GB lying around
  - Storage:
    512 GB NVME
    250 GB SSD (was a cache drive I was originally using for my Unraid Server)
    1 TB SSD (was another drive that I was using for my Unraid server)
    2 X 1 TB HDD (Very old hard Drives I have not needed but had lying around)

What you choose for your hardware is your choice, and by no means do you need as much storage as I put, as I just had them lying around and needed to find some purpose for them. With 6 Corese and six threads, this machine can run the virtual environment I set out to make. 
