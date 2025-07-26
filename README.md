Quote for the mind:    
Great minds discuss ideas; average minds discuss events; small minds discuss people.    
Eleanor Roosevelt

# Boot-Linux-OS-with-Windows-11-(Dual-booting-OS)
Before starting this project, I highly recommend reinstalling Windows 11 OS on a clean disk. Why?   
If you will are using openSUSE Linux as main OS for web servers, vm host, or data backup (/vars logs included),   
then you will need added disk space for data, and storage pool.   
Highly recommended: [Install Windows 11 on a clean disk](https://github.com/axruffin2055/How-to-install-Windows-11-on-a-clean-disk)

Now...
Say goodbye to Windows Sub-system for Linux (WSL2).

Introduction:    
If you have Windows 11 and you are using Windows Subsystem for Linux (WSL2), just know, that I feel your pain. I was using Linux kernal 
with Linux's distributions such as Debian and Ubuntu (Just a Linux command line tool). And while it was great using WSL2 as a virtual machine
that mounts Linux Kernal to use distributions for software configurations, package managment, file system interaction, and network enhancements,
I believe half of the problems I experienced with WSL2 would have not existed if I was using an Linux native or Linux OS because even though
Linux is compatible with a wide range of hardware and software, WSL2 is Windows and will not be forgiven on compatibilities because Windows and WSL2
(Linux kernal and distribution) runs side by side. Thus, while Linux compatibility is saying yes on software or hardware, you will run into  
problem with Windows 11 because WLS2 act as a virtual machine or a container.

Objective:
- Install openSUSE alongside Windows 11
- Replacing or supplementing WSL2.
- Walk you through the process of partitioning your Windows disk.
- Setting up openSUSE, and ensuring a smooth dual-boot system.


Description:    
We are setting up a dual-boot system with Windows 11 and openSUSE Linux, which will replace or move away from Windows Subsystem for Linux (WSL2). By setting up a dual-boot system, you can enjoy the best of both worlds (Windows 11 & Linux OS). OpenSUSE OS will better help solidify your Linux learning and administrator development, server management, and Linux-specific tasks. Last, this project will help individuals who are facing performance or compatibility limitations with WSL2 and wish to migrate to a full Linux installation.


Technologies Used: 
- openSUSE: Leap (Or Tumbleweed)
- Bash
- GRUB           (Grand Unified Bootloader)
- EFI System Partition (ESP)
- zypper         (Package Manager)
- YaST           (Primary tool used during the openSUSE installation process)
- parted         (Disk Partitioning Tool)
- xfs, btrfs, and ext4 file system
- LVM            (Logical Volume Management)
- EFIBootmgr     (UEFI Boot Manager)

Prerequisites:
- Windows 11 already installed.
- A 2 GHz dual-core processor or better.
- 4 GB system memory or more.
- 25 GB of free hard drive space or more.
- USB installer media for openSUSE.
- A backup of important data.
- Internet access for downloading openSUSE ISO and updates during installation.




    



Installation: 



Usage: 
Show how to use the project after installation
