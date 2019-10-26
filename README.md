# TTR-Linux-Launcher-Fix
A Fix to run the Toontown Rewritten Linux Launcher on Linux Desktops

![example](https://i.ibb.co/br6N2g5/image.png)

# How To Use

1) Download the TTR.sh file from this git repository.
2) Download the Offical Linux Launcher from TTR's Website
3) Make a folder in your home folder called Games
4) Make a folder inside of Games called TTR
5) Edit the .sh script to include your home directory on the **cd** line
6) Test running the .sh script. It should work
7) Download the toontownrewritten.desktop file to your desktop
8) Edit the file to change the home directory to yours.
9) Type **"sudo mv Toontown\ Rewritten.sh /usr/share/applications"**
10) Search for TTR in your start menu

Also if you display is glitched try copying settings.json into your TTR folder.

# Why this works

Debian, what powers ubuntu has some graphics issues, so simply unsetting them before running Toontown Rewritten Fixes this

The reason the cd to the directory is needed is because if you do a shortcut onto the desktop then it will add the phase files to the desktop

# Tested Distros

- Ubuntu 18.04
- deepin 15.11
- Linux Mint
- Debian Stable 9
- Zorin OS 15
