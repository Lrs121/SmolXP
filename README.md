# SmolXP (ARCHIVED)

## Archival Notice
**This project has been archived.** This was just the result of me messing around with nLite for the first time. Someone can easily replicate what this project does within 5 minutes, and I also don't want to be the known as the person who slimmed Windows XP down as far as I could while making it still functional. I cannot believe that out of all of my projects, *this one* was the most popular. I also feel like deleting it but still deciding.

**If you want to see stuff that I actually put proper time and work into, then please look at my other projects.** This project is just really small modifications in nLite that anyone could do easily. It's nothing special or even anything impressive. **PLEASE**, I beg of you, go check out my other projects on my profile or either check out my best project so far, [LUM/MARINER](https://github.com/AFellowSpeedrunner/LUM-MARINER), which could do with some contributions.

## Description
SmolXP is a compact version of Windows XP designed for use on low-performance computers or as a disposable operating system for testing purposes. Its small ISO and installation size make it suitable for use on older computers with limited resources. 

This project was inspired by the custom Windows version Tiny10 and Tiny11 by NTDEV. 

Incredibly, SmolXP is able to run with just 24MB of RAM and 32MB of VRAM.

With VMware Tools installed with no pagefile and compression enabled, it can take up only 100-400MB of space on a 5GB storage medium.

Installation doesn't take long. I didn't time that but if I had to say depending on what specs your using it could take 3-10 minutes. Much faster than normal XP.


SmolXP 2.0's x86 and x64 version side by side.
![image](https://github.com/AFellowSpeedrunner/SmolXP/assets/73440604/bed5c63e-f998-444c-ae71-b810e71caadd)

## So what happened to the previous name "TinyXP"?
Turns out it was already used in 2008 by someone else. I will not change the older versions to include the new name. That would take too much time. This project now goes by "SmolXP" as suggested again by [@yum13241](https://github.com/yum13241).

## Virtual Machine Software that can install and run SmolXP
VMware Workstation 17
VirtualBox (Guest Editions doesn't work right in x64.)

## Known Fixable Issues
### Nothing so far.

## Known Unfixable Issues
### VBox Guest Editions don't work correctly with x64.
This is seems to be more an issue with Windows XP x64 itself, and less to do with SmolXP x64. If it works fine in SmolXP x86 then why doesn't it work in x64? It can't of been something that nLite did, the settings would of been the exact same. Therefore, I think it's just an issue with the code for XP x64. This is unfixable for the time being and probably will never be fixed. Go use VMware or QEMU for full support in x64, use VirtualBox if you want but be aware you will not have proper support.

## Fixed Issues
### WPADISABLE.bat
A patch has been rolled out in Release 1.3.

### Automatic Drive Wiping during TextMode Setup
A patch has been rolled out in Release 1.2.

### Product Key error during Graphical Setup
A patch has been rolled out in Release 1.2.

### Random signon bug
A patch has been rolled out in Release 1.2.

### Activation
A patch has been rolled out in Release 1.1.

All bugs above were fixed by [@yum13241](https://github.com/yum13241). Huge thanks! All credits for these patches go to [@yum13241](https://github.com/yum13241).
