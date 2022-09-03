# PocketCHIP-i3wm
A guide for i3wm on the PocketCHIP, partially based on [this](https://github.com/justinwash/PocketCHIP-i3wm).
This was made for debian 9 but can also work on other versions.

1. Install i3 and PocketDESK:
```
sudo apt get-update
sudo apt-get upgrade
sudo apt-get install i3 i3blocks git
git clone https://github.com/AllGray/PocketDesk.git
sudo ./PocketDesk/PocketDESK.sh
```

2. Clone this repo and copy files, you can also copy them manually. It is important to do this before you reboot, because your PocketCHIP probably wont boot successfully without the xorg config!
```
git clone https://github.com/v1nc/PocketCHIP-i3wm
sudo cp -R PocketCHIP-i3wm/* /
```
3. Set permissions for binaries:
```
sudo chmod +x /bin/battery
sudo chmod +x /bin/brightness
```

3. Reboot, select i3 at the xfce screen, login and enjoy
