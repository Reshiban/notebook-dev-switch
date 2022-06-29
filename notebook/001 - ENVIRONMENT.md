# 001 - ENVIRONMENT.md

# 📖 Chapters
- [I - Presentation](#i---presentation)
  - [You'll need](#youll-need)
- [II - Computer [needed]](#ii---computer-needed)
  - [OS (Windows, ~~Mac OS~~, Linux)](#os-windows-mac-os-linux)
  - [devkitPro](#devkitpro)
  - [Switch Emulator (Yuzu, Ryujinx...)](#switch-emulator-yuzu-ryujinx)
- [III - Nintendo Switch [recommended]](#iii---nintendo-switch-recommended)
  - [CFW (Atmosphère)](#cfw-atmosphère)

# I - Presentation
First of all, we have to define and setup our working environment.<br>
No matter how much time you'll dev, all these components will usualy be needed to properly **dev**, **make** and **test** your programs.<br>


### Needed materials:

- **Computer (needed)**
  - dev/build/test
- **Nintendo Switch (recommended)**
  - test

# II - Computer [needed]

You **MUST** use a computer to dev properly on Nintendo Switch.<br>
<br>
Tasks covered by the computer:<br>
- programmation (your best C/C++ editor)
- build (compilator)
- test (emulators)
<br><br>

## OS (Windows, ~~Mac OS~~, Linux)

You **can** use any of these 3 operating systems, since you can **dev** and **build** on all of them.<br>
Btw, that's IMPOSSIBLE to **test** homebrews on Mac OS (no emulators), except if you have a Nintendo Switch.<br>
(since the issue is Vulkan and OpenGL has poor compatibility with Apple CPU, even VMs will NOT help...)<br>
<br>
Operating Systems:
- **Windows** [Recommended]
- ~~Mac OS~~ [NOT recommended]
- **Linux** [Recommended]


### Windows
Majority of the population use a Windows 10 system on their computer.<br>
It's **RECOMMENDED** to use it (if that's your actual OS), since the community made possible **dev, build, and test** homebrews on this popular OS, so **many people** can use it.<br>
<br>
NOTE: Please use the Windows 10 version of the OS (older and newer versions might be incompatible with some tools)

### ~~Mac OS~~
A handful of people are using Apple devices as main computer.<br>
It's **NOT recommended** to use it, since it's possible to **dev, and build** homebrews, but impossible to **test** them on this OS ([emulators aren't stables and available on Mac OS](https://github.com/yuzu-emu/yuzu/issues/6049#issuecomment-794328802)).

### Linux
Many people who like liberty, advanced usage, community... use a Linux system.<br>
It's **RECOMMENDED** to use it (if that's your actual OS), since the community made possible **dev, build, and test** homebrews on many distributions (prefer popular dists like Ubuntu)
<br><br>

## devkitPro

### About devkitPro
[devkitPro](https://devkitpro.org/) is a collection of GNU compilers with additional tools and libs, to dev and build for Nintendo consoles.<br>
It's the tool which will convert a C/C++ code trough a compilation.<br>

### Install devkitPro

Install **devkitPro** through these links:
- [devkitPro Windows](https://devkitpro.org/wiki/Getting_Started#Windows)
- [devkitPro Mac OS](https://devkitpro.org/wiki/Getting_Started#macOS)
- [devkitPro Linux](https://devkitpro.org/wiki/Getting_Started#Unix-like_platforms)

**(Be sure to SELECT Nintendo Switch packages)**

### Additional infos devkitPro

[devkitPro installer](https://github.com/devkitPro/installer/releases) manages and install all packages trough [pacman](https://devkitpro.org/wiki/devkitPro_pacman), the default Arch Linux packages manager.<br>
Once all finished, your system includes **GNU compilers**, **tools** and **libs** for Nintendo Switch compilation, and **MSYS2 (Mingw-w64)** for Windows compilation.<br>
<br>

## Switch emulator (Yuzu, Ryujinx...)

# III - Nintendo Switch [recommended]

A Nintendo Switch is only **recommended** so it's **optional**, since you can run and test homebrews on emulators.<br>
<br>
It's recommended because:<br>
-that's better to test your homebrews on real hardware (real console is often the platform where people will use them)<br>
-you need to own a Nintendo Switch to play copyrighted contents on emulators, since you need Switch keys to decrypt games (legaly obtainable by dumping them with [Lockpick_RCM](https://github.com/shchmue/Lockpick_RCM) from your own device)

## CFW (Atmosphère)

-------------------------

**TODO:**<br>
-Complete devkitPro, Switch emulator, CFW<br>
