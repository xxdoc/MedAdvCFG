# MedAdvCFG - Mednafen Advanced Configuration Tool

Frontend for <a href="http://mednafen.fobby.net/releases/">Mednafen</a> v0.9.38.x

Tested with the following System Cores:

GB,GBA,GG,MD,NES,PCE/PCE_FAST,PSX,SNES,VB

Homepage: http://www.nigeltodman.com/2016/06/05/medadvcfg-v0-0-1-mednafen-v0-9-38-x-frontend/

<img src="https://i.gyazo.com/a5618717f9bb303c9860c138c9a704f9.png">


v0.1.4 06-19-2016 1:27 AM


Reorganized main controls

Added Social Media Links/Icons

Now supports custom parameters


v0.1.3 06-18-2016 9:34 PM


M3U Generation now supported!

Select File - Generate Multi-Disc M3U. Enter # of Discs, Select them. Done

Outputs multi.m3u into current folder for MedAdvCFG.exe

Support Controller Selection (PSX Only for now)

Added Players Count, Will add this many input(x) to command line for controller


v0.1.2 06-17-2016 5:44 PM


Supports toggle of untrusted_fip_check parameter.

Used for Multi-Disc games specifying CUE/BIN in diff folders

Supports Multi-Disc games via M3U file.

M3U Generation coming in next build.

Now saves RomPath.

If RomPath or BiosPath exists, Resetting defaults to that path


v0.1.1 06-12-2016 12:48 AM


Now supports custom Save/Memory Card/State path

Remembers Bios/Firmware Path

Now validates every PSX Bios that has been dumped to date!

Selection of PSX Region now supported.

Auto selects PSX Region based on BIOS Region if known.

Now actually passes PCE/PSX Bios to cmdline

Resized main form slightly


v0.1.0 06-07-2016 6:08 PM


Suppresses 'Reset ROM/BIOS' Confirmation if a ROM/BIOS is not set.

Now passes video.fs 0 if Fullscreen is unchecked.

Now passes videoip 0 if Bilinear interpolation is unchecked.

Turns off MD5 Checks on System Core change.

Release compression changed to zip format

Changelog now has timestamps


v0.0.9 06-07-2016


ROM/BIOS MD5 Check is now optional

(Note: Works just fine on small bios/rom/cue. But takes time to md5 an entire iso)

Realigned ROM/BIOS 'Set' buttons

Added Mednafen icon.

Global Scaling Factor now saved with 'File -> Save Settings'

Fullscreen Resolution Override now saved with 'File -> Save Settings'

LastPath is now saved with 'File -> Save Settings'

More links in 'About' dialog


v0.0.8 06-06-2016


Reorganized main form controls

Clicking Mednafen EXE/ROM/BIOS MD5 Copies it to clipboard

Added Mednafen logo. Click it to go to Mednafen Homepage.

Added Global Scaling Factor. Applies to all axis, fullscreen and windowed.

Added Fullscreen Resolution Override.

Video Scaler settings are now actually passed to cmdline



v0.0.7 06-06-2016


Tested with PCE/PCE_FAST System Cores

Now supports more Cartridge Based Consoles (GB/GBA/GG/MD/VB)

Adds notice that PCE and PSX Cores expect a BIOS Image w\ filenames

Automatically unsets and disables Sanity Checks on all Cores but PSX

Added button to Clear BIOS/ROM



v0.0.6 06-06-2016


Now supports Cartridge Based Consoles (Tested NES/SNES)

Omits -loadcd parameter on all Cores except PSX, PCE, PCE_FAST

Uses -force_module on all cores except PSX, PCE, PCE_FAST

Added detection for some 0.9.37 Builds


v0.0.5 06-05-2016


No more typing paths by hand!

Added Drive/Folder/File Selection panel

Auto collapses on File Selection

Now performs validation of MedEXE,ROM and BIOS on each change.


v0.0.4 06-05-2016


Added detection for v0.9.38.5 x86/x64

Reviewing Command Line is now optional


v0.0.3 06-05-2016


Added Frameskip

Enabled BIOS Sanity Check

Enabled ROM Sanity Check

Enabled Temporal Blur

Enabled Temporal Blur Accumulate color

Enabled Temporal Blur Amount

Enabled Bilinear interpolation


v0.0.2 06-05-2016


Resized main form slightly

Changed colors

Added HotKeys to main form

Published to GitHub https://github.com/Veritas83/MedAdvCFG


v0.0.1 06-05-2016


First release!

Only PSX System Core is tested.
