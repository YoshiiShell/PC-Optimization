We got the hardware! Let's get the operating system now. But before that we have to do a few things.

### If you're planning to follow this from an existing Windows installation, move onto Optimizations.md

## BIOS updates

The BIOS (Basic Input Output System) is what boots the computer and the hardware behind it. It also loads the "Bootloader" of your operating system.

This BIOS can be updated in a couple ways. However the easiest (excluding updating it after OS installation) is through a flash update on a USB stick.

I'd recommend updating through OS unless you absolutely have to do it before. Like if your CPU is unsupported without a BIOS update. In this case:

### Do this only if you are comfortable to do this!

On a different computer go to your computer's or motherboard's website and grab a BIOS file or installer which should contain it.

Put it on a FAT-32 formatted USB stick and put it into your new computer.

Open the BIOS by spamming either the F2, F10, F12 or DEL key. If none of those work, check the computer's or motherboard provider's manual.

The BIOS update flash can be in various different spots within the BIOS menu. However most of the time its either on the first screen, has it's own section, or is in an advanced section.

It has various different names. 

ASRock: Instant Flash

Asus: EZ Flash or EZ Flash 3

Gigabyte: Q-Flash

MSI: M-Flash

[this is where I got it. Go check them out](https://www.tomshardware.com/how-to/update-bios-on-a-pc)

Now select the only file (if there is multiple, make sure there is **one** .rom. If not, cancel out and troubleshoot.

Let it update and once it does, it will restart you back to BIOS, or restart normally. Which then you should see Windows on a prebuilt, or a no OS found error on a custom-built.


## Drivers

Sometimes you have to grab drivers for Windows to read your disk. 

So grab your drivers from the disk provider's website and place it in an easy to access but safe kept folder. Such as a "Drivers" folder on your desktop. 

Now let's move onto installing Windows!

## Installing Windows

Hop on over to [UUPDump](https://uupdump.net/fetchupd.php?arch=amd64&ring=retail) or its [ARM64 version](https://uupdump.net/fetchupd.php?arch=arm64&ring=retail)

For AMD64 (x86_64) click the bottom one and for ARM click the only one

Select your language then click "Next"

Then choose whatever versions you will need. Only select one version unless you have a reason for multiple

Keep everything as is and click "Create download package". This will download a .zip

Unzip that and go into the folder

Run the .cmd as administrator and wait. Soon you'll see an ISO. Now put that on Rufus or Ventory or even InstallWindowsWithoutUSB

Now lets install this in install.md
