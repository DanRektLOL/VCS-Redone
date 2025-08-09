# VCS-Redone
A couple of mods I bundled together for GTA VCS. The list of mods used is given below:-
1. [Improved Vehicle Lights, Project2DFX, and Widescreen Fix](https://github.com/ThirteenAG/WidescreenFixesPack/releases?q=Grand+Theft+Auto+Vice+City+Stories+Widescreen+Fix+%5BPCSX2F%5D&expanded=true) by Thirteenag
2. [HD HUD](https://gtaforums.com/topic/983317-grand-theft-auto-vice-city-stories-hd-hud-for-pcsx2/) by Tervel1337
3. Upscaled textures by [Bl4ckH4nd](https://gbatemp.net/members/bl4ckh4nd.609354)
4. [GTA VCS Texture Pack PS2](https://github.com/ASI-Factory/GTA-VCS-Texture-Pack-PS2) by ASI-Factory
And I think that's all, if you think I used a mod of yours, reach out to me at @danrekt on discord, and if any of the authors have a problem with me using their mods, reach out to me and I will take this repository down.

Works with the SLUS-21590 version of the game.
Keyboard is not fully supported so dont open an issue related to keyboard support. It can be enabled in GTAVCS.PCSX2F.WidescreenFix.ini.

# Installation

You will need to provide your own (US) GTA VCS ROM and PS2 firmware dumped from a PS2.

Step 1. Download V 1.0.2

Step 2. Drag n drop your ROM iso in Games folder

Step 3. For 1st time setup, you will have to launch pcsx2-qtx64-clang.exe and go to settings>controllers>controller port 1>Automatic mapping and click on your controller.
                                  (For KB support go to Hotkeys and make sure all of them are unbound by right clicking them.)
             Now, you can open pcsx2-qtx64-clang.exe and double-click Grand Theft Auto Vice City Stories to start playing.

Step 4 (optional, for best gaming experience) To make a shortcut, rename your .iso to VCS.iso, now right click the top, where it tells your folder address, and press copy address as text.

Now open up PlayVCS.txt, in your pcsx2f folder, and paste your folder address right before it says \VCS.iso. Now, it should be, for example
                        START pcsx2-qtx64-clang.exe "D:\ExampleFolder\VCS.iso
Now save it and close it, now rename it to PlayVCS.bat. Now, you can run this to run the game.
Right-click it, send to desktop, and you got yourself a working VCS shortcut.

# Known bugs

/ For certain missions, like Boomshine Blowout, you will have to go to PLUGINS\GTAVCS.PCSX2F.WidescreenFix.ini and change 60FPS To 0
/ Windows on buildings are completely transparent which looks a bit odd, but just live with it, I think I could fix it, if anyone has a problem with them, open an issue, and I'll see what I can do.

# I CLAIM NO CREDIT FOR ANY OF THIS.
Tutorial is only really for Windows 10 and 11. Compatibility with other OSes unknown.
