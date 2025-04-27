Let's install Windows! You have two options. Either through a USB stick or through InstallWindowsWithoutUSB.

### If you're planning to follow this from an existing Windows installation, move onto Optimizations.md. If you are planning to dual boot with an optimized Windows, follow this.

## USB

If you have a USB stick (formally known as a mass storage device), use [Rufus](https://github.com/pbatard/rufus/releases/download/v4.5/rufus-4.5.exe) to flash it on the USB.

You should then restart the system. During boot, spam the BIOS key or the boot order key. usually F2, 12 or del. Boot to the USB and you should be at the Windows install screen.

## InstallWindowsWithoutUSB

Yes, you can install Windows without a USB stick and I'd say it's better than a USB in fact. Click on [this to download the program](https://github.com/iidanL/InstallWindowsWithoutUSB/archive/refs/heads/main.zip) and unzip the ZIP.

Then run the batchfile as administrator and follow the instructions. Then reboot and you should be at windeploy.

# Installing Windows pre-OOBE

### USB

For region, choose "World" then change nothing and follow instructions. After it reboots, you will have to wait for Windeploy. 

### All

Now both types of users should be at Windeploy. Now wait for OOBE.

# OOBE

## Pre-account setup

Now you should be in OOBE (Out-Of-Box-Experience).
If you get an OOBEREGION error, just skip it.

## Accounts

### Windows 10
If on 10, just click the button "Domain Join" on the account creation screen, and we will meet you at the privacy setup screen.

### Windows 11

DIsconnect your Ethernet first.

Choose whatever language and region you are in. Once on the network screen, press Shift and F10 and type in ```start ms-cxh:localonly``` and it will restart.
[Here's why and how it works](https://github.com/YoshiiShell/PC-Optimization/blob/main/Advanced%20discussions.md#start-ms-cxhlocalonly-how-does-it-work)

On network setup choose "I dont have internet" and it'll take you to local account creation.

## Privacy setup

Welcome back Windows 10 users. Both 10 and 11 users should turn off all the privacy setup, and if asked for a Cortana setup, click anything similar to not now or tell me later. In a few moments, you should be in Windows!
