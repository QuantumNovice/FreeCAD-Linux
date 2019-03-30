# FreeCAD Linux

Custom built minimalistic linux distro built directly from linux-kernel (slax) to run FreeCAD 0.16.
Preinstalled:
-------------
* Addon Manager
* BIM Workbench

How to Install:
===============
For systems that support boot from USB:
------------------------------------
Windows:
--------
* Download freecad_slax.7z from https://drive.google.com/open?id=1bTcwSm1KC2Eyl4xn5GH1_5915Oy9s7_o with 7zip.
* Extract the contents zip to USB drive.
* Goto slax/boot folder and run bootinit.bat from the extracted files in usb.
* You are set to go.

Linux:
--------
* Download freecad_slax.7z from https://drive.google.com/open?id=1bTcwSm1KC2Eyl4xn5GH1_5915Oy9s7_o with 7zip.
* Extract the contents zip to USB drive.
* Goto slack/boot folder and run bootinit.sh from the extracted files in usb.
* You are set to go.

How to Boot:
============
* Restart your PC.
* Press F9 (or other key according to your PC to display boot options).
* Select boot from USB.
* Wait and you are ready to go.

Testing Log:
=============
Test 1:
-------
(Current Version)
* Linux Kernel + FreeCAD 0.16 + Slax ==> FreeCAD Slax (Very Stable)
* Pre-Installed BIM
* The graphics doesn't look cool because of Qt4 update ASAP.

Test 2:
-------
Linux Kernel + FreeCAD 0.17 + Slax ==> Unstable

Test 3:
-------
Linux Kernel + FreeCAD 0.18 + Slax ==> Unstable

Test 4:
-------
ParrotOS (Debian Buster): + FreeCAD 0.18 ==> Very Stable
This version is much faster but occupies more space.



# Important Paths
* /run/initramfs/memory/data/slax
* /usr/share/freecad/Mods
* cat somewallpaper.jpg > /usr/share/wallpapers/slax_wallpaper.jpg
