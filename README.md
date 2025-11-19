<div align="center">

# 🎮 Game Specific Patches & DLL Wrappers  

***created and maintained by***

[![Chip-Biscuit Website](https://img.shields.io/badge/Chip--Biscuit-Website-blue?style=for-the-badge)](https://chip-biscuit.github.io/)

Reverse Engineering • Programming • Patching • Game Improvements • DLL Creation 

</div>

---

# 102 Dalmatians (PC) — Modern 64-bit Installer Port  
A complete 64-bit replacement installer for the original PC release, designed for long-term preservation and modern Windows compatibility.

---

## Why This Installer Exists

The original Windows release of *Disney’s 102 Dalmatians: Puppies to the Rescue* includes a 16-bit installer which cannot run on any 64-bit version of Windows (Vista through Windows 11).  
To preserve the game and ensure it remains playable on modern systems, I recreated the original install process as a custom 64-bit installer.

This installer:

- Requires the original English retail PC disc  
- Does not redistribute any copyrighted game files  
- Replicates the logic of the original installer  
- Includes optional modern fixes (DXWrapper and full controller support)

---

# Installation 

Go to the releases section and scroll to the bottom of the page then download Chips64bit_102DalmatiansInstaller.exe you can run it from anywhere, just make sure that you have the English original disc of the game mounted and then you can point the installer to that disc.

Then just follow the instructions in the installer and it will create a shortcut on your desktop then you can run that and play the game. 

---

# Requirements

### You must own the original English retail PC CD  
No game files are included.  
The installer checks the SHA-1 hash of the disc’s `PCDOGS.EXE` to ensure the correct version is being used.
You must have the disc of the game mounted on your pc for this installer to work. 

### You must point the installer to your CD or mounted ISO  
Typical disc locations:
```
D:\
E:\
F:\
```

On the first screen, browse to your mounted disc and proceed through the installer normally.

---

# Features

### Full XInput Controller Support
Compatible with:

- Xbox One / Series controllers  
- Xbox 360 controllers  
- Controllers emulating XInput (DS4Windows, x360ce, etc.)

### DXWrapper Integration
Includes Elisha Riedlinger’s DXWrapper with improvements such as:

- Widescreen support  
- Anti-aliasing  
- Anisotropic filtering  
- Crash fixes  
- Modern DirectX compatibility
- Can be a little buggy with more than one monitor i would suggest just playing this game with 1 monitor and it runs absolultely perfectly. 

All features can be adjusted in `dxwrapper.ini`.

### Clean Uninstall Support
All files installed by this installer are removed when uninstalling the game.

---

# Controller Support Add-On

Included with the installer optionally.

This re enables the original xinput controller support for the game. 

You can edit the controls in the game control options by clicking on a joystick input pressing the button you want on the controller and pressing enter on the keyboard then save and you have the controls you want.

If launching the game through Steam, disable Steam Input in the game’s controller options.

---

# Alternative User Profile for Controller Support (PCGamingWiki)

[![PCGamingWiki](https://img.shields.io/badge/PCGamingWiki-File%20Page-0066cc?style=flat&logo=pcgamingwiki&logoColor=white)](https://community.pcgamingwiki.com/files/file/3729-chipxinput-102-dalmatians-controller-calibration-fix/)

(This is for D3D9.dll and D3d9.INI for the controller support part)

It is possible on some versions of the game the pcgw method may cause crashing.

Example layout with the above method:

<img width="1920" height="1080" alt="102dalmatians" src="https://github.com/user-attachments/assets/0e8594d5-0290-49fe-bcd6-333ae533348a" />
---

# Credits

- Elisha Riedlinger — DXWrapper  
- Elisha Riedlinger and ThirteenAG — base Direct3D9 wrapper.

---

# Issues and Support

For help, please visit the Discord server:  
https://discord.gg/eVJ7sQH7Cc

---

# About Chip

Creating compatibility fixes and enhancements for legacy PC games.

- Reverse engineer  
- Programmer  
- Developer  

<img width="250" alt="my logoo" src="https://github.com/user-attachments/assets/9bb13d3f-0734-4f1d-b68f-14114b13744a" />

