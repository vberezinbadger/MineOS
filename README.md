## mineOS has released

### Greeting

Hello again, dear friend. Thank you for being with us and supporting our ideas throughout the long development cycle. mineOS has finally reached the release stage: now it is a completely independent operating system with its own development API and wonderful [illustrated wiki](https://github.com/IgorTimofeev/mineos/wiki) of it's usage. 
mineOS is a GUI based operating system for the Open Computers Minecraft mod. It has extensive and powerful customisation abilities as well as an app market to publish your creations among the OS community.
Here's a list of a few features:

-   Multitasking
-   Double buffered graphical user interface
-   Language packs and software localization
-   Multiple user profiles with password authentication
-   Own EEPROM firmware with boot volume choose/format/rename features and Internet Recovery mode
-   File sharing over the local network via modems
-   Client connections to real FTP servers
-   An internal IDE with syntax highlighting and debugger
-   Integrated application and library App Market with the ability to publish your own scripts and programs for every MineOS user
-   Error reporting system with the possibility to send information to developers
-   Animations, wallpapers, screensavers, color schemes and huge customization possibilities
-   Open source system API and detailed illustrated documentations

### How to install?

The easiest way is to use default **pastebin** script. Insert an OpenOS floppy disk to computer, insert an Internet Card, turn computer on and type the following to console to install MineOS:

      wget -f https://raw.githubusercontent.com/vberezinbadger/MineOS/master/Installer/BIOS.lua /tmp/bios.lua && flash -q /tmp/bios.lua && reboot

In mineOS has a MineBash application (available both in the new mineOS and in the old and original MineOS, but without support for hardware functionality). Install the MineBash application to easily launch the kernel, install terminal programs and applications for it.

After a moment, a nice system installer will be shown. You will be prompted to select your preferred language, boot volume (can be formatted if needed), create a user profile and customize some settings

### How to create applications and work with API?

[Wiki (MineOS Original)](https://github.com/IgorTimofeev/MineOS/wiki)
