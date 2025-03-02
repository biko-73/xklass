# XKlass by KiddaC - Official Release - The Final Frontier.

V 1.37 - 27/02/2025 :face with monocle:

Plugin is for playing official Xtream Codes/XUI ONE IPTV playlists.
This plugin is a rework of my XStreamity plugin but with all new layout and new side menu accessible by the "Menu" button.
This plugin only plays xtream code playlists and does not play other playlists or m3u playlists.

https://github.com/kiddac

Do not post personal MOD code in this thread, including different functionality, different skins etc. It confuses me, it confuses users.
Also we test most code on multiple images and boxes. Modifications might work on your setup, but may crash other peoples.
Start a new thread if need be quoting it is a mod and what images/box it is has been tested on.

This plugin does not contain any playlists or channels. All IPTV playlists need to be sourced by user.
IPTV is perfectly legal - IPTV providers/playlists that contain unscrambled encrpyted channels are illegal. User is responsible for any downloaded playlist content.
We do not discuss IPTV providers on this forum.
I don't recommend, promote or have an affiliation with any provider. Questions regarding IPTV providers will be ignored/deleted.
Do not post IPTV provider names, provider URLs, provider IP addresses, or screenshots that identify providers in this thread.
Check any posted crash logs do not contain any of your provider, username & password details.
It is recommend you use a VPN with any IPTV plugin. VPN use is not the topic of this thread.

XKlass should be compatible with all images and boxes.

# Installation

XKlass is available in lots of image feeds under plugins / download plugins / extensions. The 100% latest version can always be found on post 1 of this thread.
Feeds are sometimes a little behind.

openpli 8.3+ / openpli 9 please install from plugin feeds first to load required dependencies. (Xstreamity plugin in feeds will also load the dependencies)
Then you can load the latest from this forum over the top.

# How to manually install .ipk on OE-Alliance images via telnet
To manually install, copy ipk to tmp folder

then telnet/ putty
opkg install /tmp/*.ipk

# How to manually install .deb on DreamOS via telnet

To manually install, copy ipk to tmp folder
then telnet/ putty
dpkg -i /tmp/*.deb

apt-get update
apt-get install -f
press Y key to finish installation when asked

# Dependencies
In the majority of cases the plugin will automatically install all the required dependencies required for XKlass.
Rarely this fails and the user will need to ensure all dependencies are installed currently via telnet/putty
If you are getting repeated dependencies console screen. Try these commands

# Python 2
opkg install python-requests
opkg install python-multiprocessing
opkg install python-image
opkg install python-imaging
opkg install wget Full wget is required for https lines and used by the download manager.

# python 3
opkg install python3-requests
opkg install python3-pillow
opkg install wget Full wget is required for https lines and used by the download manager.

# Dreamboxes
apt-get -y install python-requests
apt-get -y install python-image
apt-get -y install python-imaging
apt-get -y install wget Full wget is required for https lines and used by the download manager.


# Dreamboxes - python3
apt-get -y install python3-requests
apt-get -y install python3-multiprocessing
