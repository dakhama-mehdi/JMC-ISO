![cmc-iso-2 0 9](https://user-images.githubusercontent.com/49924401/133791133-33d9f930-b1d4-4a67-bfbd-e3631d1bd1bd.gif)

# CMC-ISO Version  : 2.0.9
* Free Tool
* Tool to Create Media Windows 10, Windows server Boot 
* Support Booth mode uefi-legacy bios- and Secureboot
* Download all support version Win10 Retail with any language from official microsoft site 
* Support iso generated by MDT or SCCM
* Availble in the Microsoft Store

# What's News :
* Add automatically language chose
* Scan files copy in real time
* New language Spanish and Italian
* calcul SHA256 and check authenticity windows ISO from database (no support evaluation iso)
* Scan files with AV during copy (detect vulnerability file when created a media drive)
* Support another distribution Winpe (Amoei, Acronis, DaRT, Hirensboot, malekal, all liveCD will be worked on dual boot BIOS/UEFI and SecureBoot)

This free tool offres two fonctionality. 

* Burn your ISO on you USB Drive or External Hard Drive - and boot on UEFI OR Legacy mode support SecureBoot
* Download Windows 10 ISO all Version
* Support Amoei, Hirensboot, Malekal
* check Windows ISO SHA1 and validity


# Why to use : 

* CMC-ISO, is one of few tool that keep you to burn your iso on USB and also external hard drive
* Support Secure Boot
* Create Universal Media compatible with UEFI and Legacy Bios Mode
* compatible all version Windwos 10 ISO (WIM or ESD) (RTM and Retail)
* dont need install, very fast, and tool is signed and verified 

# prerequiste
* tool work only on Windows 8.1 or Win 10
* you must have Powershell version 4.0 min
* have media USB or External hard drive have more 8 GO

# How to use :
* for create a usb media boot, select Image ISO, select your Drive, Select mode Boot (Universsel support UEFI + LEgacy) or (MBR for old Bios)
* if your image is generated by MDT or SCCM pls use the external hard drive and not flash drive
* clic donwload to chose a windows 10 version with language and edition 
Links video : https://youtu.be/6btXXqodldU

# One note on Microsoft’s tool. This tool has some limitations:

* Each time you run it, it fully downloads the media from the internet. This makes it a much longer process if you are needing to re-do the process or setup multiple drives
* It is only the latest version of Windows. Right now, 2004 is the latest version, but if you needed 2002 or earlier it does not give you an option to select an earlier version.
* It is only Windows 10 Pro
* You can't use your propr ISO editing or genered by MDT or ICD 
* not support ISO captured by dism
* On the upside, the install.wim is compressed to under 4GB so it can fit on FAT32 partitions and thus allow you to have only 1 partition on the key 
* Hash 2.0.9.exe is : SHA-256 = 672FCE6618427EBECF823F7B8BF1ADFF11B42D0CFC323E27F86F36BCCDA55B15


Enjoy

