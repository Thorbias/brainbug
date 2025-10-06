# Install and Configure Bazzite in a Dual Boot System
So after I started a year ago with Fedora and GNOME I got a bit bored about the smoothly running system :)
Thus I looked around for other distros or flavours of Linux which would be more gaming focused. I considered Pop_os!, Nobara, CachyOS and of course Bazzite.
Eventually I went for Bazzite because I liked the look and the package manager or call it AppStore was the most appealing to me: Bazaar.
Unfortunately Bazzite was a bit shy and didn't wanted to override my previous Fedora Installation. Actually the trouble was with Grub and I had to remove Grub before I could install Bazzite.
I found a pretty nice installation guide covering the following steps from within a running windows to clear grub (of course I wiped my fedora before I did realize that I had to clean grub as well...).
--TODO: Put the Steps here
After that the installation from a bootable USB Stick was straigt forward and did take round about 15 minutes until I got to touch the bazzite desktop.
First I checked system update and let it do its magic.
Afterwards I started to make the desktop feel comfy by resizing the task bar and installing another app launcher:
--TODO: how to install the app launcher
Than I wanted the system to directly boot to desktop without the hassle of login.
--TODO: how to directly login without pw .. System Settings->Colors&Themes->LoginScreen(SDDM)-> Behavior... in top menu->automatically log in:...
Next: Mounting my Data NVME as /home/Data folder:
--ToDO: instructions on that
Steam pointing to my SteamLibrary

Undervolting with CoreCtl -> reminder: performance mode should be automatic or not controlled (had it on low performance by accident which gave really low fps)
HOW TO INSTALL RPMS?!
--ToDo: instructions

Reminder: SetUp BT Headset properly with audio output only otherwise game sound is trashy. Use external mic for Input in Discord etc.

GRUB: boot to last chosen one (better for updates)

All fine and to my likings BUT...
Sleep doesnt work -> Solution still to be found -> Black Screen - no idea whats happening here
What is not working: GRUB options amd_immo=off etc...
List all things I tried
