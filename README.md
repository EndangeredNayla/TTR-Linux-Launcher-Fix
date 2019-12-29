# TTR-Linux-Launcher-Fix
A Fix to run the Toontown Rewritten Linux Launcher on Linux Desktops

![example](https://i.ibb.co/br6N2g5/image.png)

# How To Use

1) Download the `TR.sh` file from this git repository.
2) Download the Offical Linux Launcher from TTR's Website.
3) Put the `TTR.sh` and the Offical Linux Launcher into a folder.
4) Edit the `TTR.sh` script file to change `path/to/TTR/dir/` to the location of the folder you made in step 3.
5) Launch the `TTR.sh` File.



# Other Issues

Q: My Toontown Rewritten Game Window is Stuff in Full Screen
A: Copy the settings.json found here into your TTR game folder.

Q: How Do I Add Toontown Rewritten to my Application Launcher.
A: I would recommend using `alacarte` which should be in your Packages. The Execuatble would be the `TTR.sh` file and you can use the icon located in this repo if you wish.

Q: Toontown Rewritten is still not launching after following everything above
A: Did you name the folder where the Launcher is located with a space. There can be no spaces.

# Why This Works
The Toontown Rewritten Linux client has some graphical issues with the X Window Manager installed by defualt on some linux distros. Running This Script can fix alot of those issues that are in place.

The reason you need to CD to the directory is because if you want to make a shortcut on the Desktop or somewhere else you need to go to the directory TTR is in for the game to fully launch.

# Tested Distros
- Ubuntu 18.04
- deepin 15.11
- Linux Mint 19.2
- Debian Stable 9
- Zorin OS 15
- PopOS 19_10
- PopOS 18_04
