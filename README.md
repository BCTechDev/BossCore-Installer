# BossCore-Installer
We included some tools to replace APT, Snap, and Flatpak install/uninstalls for more novice users. These are those tools.

# How To Use
Copy the files in this repo to the /bin directory in any Linux distribution that uses APT (or any OS based on Ubuntu/Debian)
Run the command ```chmod 777 /bin```
Then type the commands:
```
install-app (to install an application)
uninstall   (to uninstall an application)
full-uninstall (to uninstall an application and wipe its cache and other data off the disk)
```
These tools, as of Version 1, works with APT, Flatpak, and Snap. We plan to add support for other systems like Pacman and Portage.

We also plan to have APT download the source for the application and compile it, for added support and to allow for usage on multiple architectures where some applications might not come natively for ARM or PowerPC.
