## FIRST THING FIRST

- [x] **Change the Repository**
	```bash
	sudo nano /etc/apt/sources.list
	```

	Repository Local Indonesia Ubuntu 19.04
	**Server Kambing.ui.ac.id**
	```bash
    deb http://kambing.ui.ac.id/ubuntu/ disco main restricted
    deb http://kambing.ui.ac.id/ubuntu/ disco-updates main restricted
    deb http://kambing.ui.ac.id/ubuntu/ disco universe
    deb http://kambing.ui.ac.id/ubuntu/ disco-updates universe
    deb http://kambing.ui.ac.id/ubuntu/ disco multiverse
    deb http://kambing.ui.ac.id/ubuntu/ disco-updates multiverse
    deb http://kambing.ui.ac.id/ubuntu/ disco-backports main restricted universe multiverse
    deb http://kambing.ui.ac.id/ubuntu/ disco-security main restricted
    deb http://kambing.ui.ac.id/ubuntu/ disco-security universe
    deb http://kambing.ui.ac.id/ubuntu/ disco-security multiverse
    ```

	**Server Kebo.pens.ac.id**
	```bash
    deb http://kebo.pens.ac.id/ubuntu/ disco main restricted
    deb http://kebo.pens.ac.id/ubuntu/ disco-updates main restricted
    deb http://kebo.pens.ac.id/ubuntu/ disco universe
    deb http://kebo.pens.ac.id/ubuntu/ disco-updates universe
    deb http://kebo.pens.ac.id/ubuntu/ disco multiverse
    deb http://kebo.pens.ac.id/ubuntu/ disco-updates multiverse
    deb http://kebo.pens.ac.id/ubuntu/ disco-backports main restricted universe multiverse
    deb http://kebo.pens.ac.id/ubuntu/ disco-security main restricted
    deb http://kebo.pens.ac.id/ubuntu/ disco-security universe
    deb http://kebo.pens.ac.id/ubuntu/ disco-security multiverse
    ```

	**Server Mirror.unej.ac.id**
	```bash
    deb http://mirror.unej.ac.id/ubuntu/ disco main restricted
    deb http://mirror.unej.ac.id/ubuntu/ disco-updates main restricted
    deb http://mirror.unej.ac.id/ubuntu/ disco universe
    deb http://mirror.unej.ac.id/ubuntu/ disco-updates universe
    deb http://mirror.unej.ac.id/ubuntu/ disco multiverse
    deb http://mirror.unej.ac.id/ubuntu/ disco-updates multiverse
    deb http://mirror.unej.ac.id/ubuntu/ disco-backports main restricted universe multiverse
    deb http://mirror.unej.ac.id/ubuntu/ disco-security main restricted
    deb http://mirror.unej.ac.id/ubuntu/ disco-security universe
    deb http://mirror.unej.ac.id/ubuntu/ disco-security multiverse
    ```

	**Server Mirror Poliwangi**
	```bash
    deb http://mirror.poliwangi.ac.id/ubuntu/ disco main restricted
    deb http://mirror.poliwangi.ac.id/ubuntu/ disco-updates main restricted
    deb http://mirror.poliwangi.ac.id/ubuntu/ disco universe
    deb http://mirror.poliwangi.ac.id/ubuntu/ disco-updates universe
    deb http://mirror.poliwangi.ac.id/ubuntu/ disco multiverse
    deb http://mirror.poliwangi.ac.id/ubuntu/ disco-updates multiverse
    deb http://mirror.poliwangi.ac.id/ubuntu/ disco-backports main restricted universe multiverse
    deb http://mirror.poliwangi.ac.id/ubuntu/ disco-security main restricted
    deb http://mirror.poliwangi.ac.id/ubuntu/ disco-security universe
    deb http://mirror.poliwangi.ac.id/ubuntu/ disco-security multiverse
    ```

    for exit & save use `CTRL + X` and than `CTRL + Y`

- [x] **Update**
	```bash
	sudo apt update && sudo apt upgrade -y
	sudo apt dist-upgrade
	```

- [x] **Check New Version**
	```bash
	sudo do-release-upgrade
	```

- [x] **Clean Up OS**
	```bash
	sudo apt autoremove -y
	sudo apt autoclean -y
	```

- [x] **Gnome Extention for Browser**
	```bash
	sudo apt install chrome-gnome-shell -y
	```

	**Gnome Extention to do install**
	- [x] **User Themes** [easily install new shell themes downloaded from the web.](https://extensions.gnome.org/extension/19/user-themes/)
	- [x] **Extention** [manage GNOME extension through a panel menu.](https://extensions.gnome.org/extension/1036/extensions/)
	- [x] **OpenWeather** [get weather updates on your Desktop.](https://extensions.gnome.org/extension/750/openweather/)

	**Download extention for Browsers**
	- [x] **Chrome/chromium** [Integrasi Shell GNOME](https://chrome.google.com/webstore/detail/gnome-shell-integration/gphhapmejobijbbhgpjhcjognlahblep?hl=id)
	- [x] **Firefox** [Integrasi Shell GNOME](https://addons.mozilla.org/id/firefox/addon/gnome-shell-integration/)


- [x] **Media Codecs**
	```bash
	sudo apt install ubuntu-restricted-extras -y
	sudo apt install libavcodec-extra -y
	sudo apt install libdvd-pkg -y
	```

- [x] **Synaptic**
	```bash
	sudo apt install synaptic -y
	```

- [x] **gtx Engine**
	```bash
	sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf -y
	```

- [x] **Archive Applications**
	```bash
	sudo apt-get install unrar zip unzip p7zip-full p7zip-rar rar -y
	```

- [x] **Thimeshift Backup system**
	```bash
	sudo add-apt-repository -y ppa:teejee2008/ppa
	sudo apt-get update -y
	sudo apt-get install timeshift -y
	```

- [x] **Java**
	```bash
	sudo apt-get install openjdk-11-jdk -y
	```

- [x] **Add Pantheon File Manager for ubuntu**
	```bash
	sudo add-apt-repository ppa:elementary-os/daily
	sudo apt update -y
	sudo apt install pantheon-file -y
	```

---

<br />

## Tweaking the UI
- [x] **Tweak**
	```bash
	sudo apt install gnome-tweak-tool -y
	```

- [x] **Make Ubuntu Like Mac Os Mojave/Cataline**
	
	**MAC THEME**
	- [x] **Sheel Theme**
			[McMojave](https://www.gnome-look.org/p/1275087/)
			[McOS-Theme CTLina](https://www.gnome-look.org/p/1241688/)
			
	- [x] **Icon** [McMojave-cricle](https://www.gnome-look.org/s/Gnome/p/1305429)
	- [x] **Icon** [McMojave-cricle](https://www.gnome-look.org/s/Gnome/p/1305429)
---
## Boosting up system

- [x] **Reduce Overheating & Improve Battery Life**
```
add-apt-repository ppa:linrunner/tlp
apt update
apt install tlp tlp-rdw
tlp start
```

- [x] **Handle 100% CPU Usage** *by [Abhishek Prakash](https://itsfoss.com/things-to-do-after-installing-elementary-os-loki/)*
```
chmod 744 /usr/lib/gvfs/gvfsd-smb-browse
```

---

<br />

## PLANK

<br />

- [x] **Proper Plank**
```
add-apt-repository ppa:ricotz/docky
apt update
apt install --reinstall plank
killall plank
plank --preferences
```

<br />

- [x] **Gnosemite Theme** *by [@P0umon](https://p0umon.deviantart.com/art/Gnosemite-theme-for-Plank-628809799)*
* For more transparency, change the last value in `/usr/share/plank/themes/Gnosierra/dock.theme` file, under `FillEndColor=110;;107;;111;;150`.

<br />

- [x] **Plank Themes** *by [@KenHarkey](https://github.com/KenHarkey/plank-themes)*

* Copy the contents of the [Plank Themes](https://github.com/KenHarkey/plank-themes/archive/master.zip) folder to `~/.local/share/plank/themes` or to `/usr/share/plank/themes` for system-wide use.

<br />

- [x] **Plank Separator** Remix *by [@rpeshkov](https://github.com/rpeshkov/plank-spacer) & [@glacto](https://glacto.deviantart.com/art/Drk-Plank-Theme-with-separator-631813715)*

* Extract [plank-separator-remix.zip](https://www.dropbox.com/s/8uqxmofhkvuftwi/plank-separator-remix.zip?dl=0) and run this command everytime you want to insert a new separator:
```
bash '/home/YOUR_USERNAME/Downloads/plank-separator-remix/plank-separator.sh'
```

---

<br />

## APPS TO DOWNLOAD & INSTALL VIA EDDY

- [x] [**Brave Browser** ](https://brave-browser.readthedocs.io/en/latest/installing-brave.html#ubuntu-16-04-and-mint-18)
- [x] telegram-desktop
- [x] vlc
- [x] kodi
- [x] sublime
- [x] qbittorrent
- [x] skype
- [x] teamviewer
- [x] gparted
- [x] kodi
- [x] wine
- [x] java
- [x] **Tusk** *Unofficial Evernote For Linux* [sourceforge.net/projects/nevernote/files/?source=navbar](https://sourceforge.net/projects/nevernote/files/?source=navbar)

- [x] **Sublime Text**
- [x] **Sublime Merge**
- [x] **WPS Office*** [wps-community.org/downloads](http://wps-community.org/downloads) *Check WPS Fonts Fix*


---

<br />

## APPS TO INSTALL & CONFIGURE VIA TERMINAL

<br />

- [x] **stuff**
sudo apt-get install flashplugin-installer pepperflashplugin-nonfree
- [x] **Restricted extras and MM Codec**
sudo apt install ubuntu-restricted-extras
sudo apt install libavcodec-extra
sudo apt install libdvd-pkg
- [x] **archive formats**
```
sudo apt-get install unace rar unrar p7zip-rar p7zip sharutils uudeview mpack arj cabextract lzip lunzip
```
- [x] **Preload**
```
apt install preload
```

<br />

- [x] **FreeCAD**
```
apt install freecad
```

<br />

- [x] **GIT**
```
apt install git
```

<br />

- [x] ~~**Cerebro** [https://cerebroapp.com](https://cerebroapp.com)~~
```
chmod a+x '/home/user/Downloads/cerebro-0.3.1-x86_64.AppImage'
```

<br />

- [x] **WPS Fonts Fix** *by [@IamDH4](https://github.com/IamDH4/ttf-wps-fonts)*
```
cd /tmp
git clone https://github.com/iamdh4/ttf-wps-fonts.git
cd ttf-wps-fonts
bash install.sh
rm -rf /tmp/ttf-wps-fonts
```

<br />

- [x] ~~**San Francisco Fonts** *by [@ronakshah](https://blog.ronakshah.net/Installing-Ubuntu-Like-A-Mac-User/)*~~
```
cd /usr/share/fonts
mkdir tmp
cd tmp
git clone https://github.com/AppleDesignResources/SanFranciscoFont
cd SanFranciscoFont
mv *.otf ../../opentype
fc-cache -fv
```

<br />

- [x] **Albert**
```
add-apt-repository ppa:flexiondotorg/albert
apt update
apt install albert
```
* Replace the icon in Wingpanel: `/usr/share/icons/hicolor/scalable/apps/` with any icon of your choice in **.svg** format. I chose this: <img src="https://image.flaticon.com/icons/svg/55/55369.svg" height="14" width="14"> by [@Yannick](https://www.flaticon.com/authors/yannick) from [www.flaticons.com](https://www.flaticon.com/free-icon/search_55369#term=search&page=2&position=42).

<br />

- [x] **Dropbox For elementaryOS** *by [@zant95](https://github.com/zant95/elementary-dropbox)*
```
git clone https://github.com/zant95/elementary-dropbox /tmp/elementary-dropbox
bash '/tmp/elementary-dropbox/install.sh'
```

<br />

- [x] **My Weather Indicator** *by [Ahmed Hassan](http://eos-snippets.blogspot.com/2013/11/add-my-weather-indicator-to-wingpanel.html)*
```
add-apt-repository ppa:atareao/atareao
apt update
apt install my-weather-indicator
```

<br />

- [x] **Sticky Notes Indicator**
```
apt install indicator-stickynotes
```

<br />

- [x] **CPU Frequency Indicator**
```
apt install indicator-cpufreq
```

<br />

- [x] **elementary+ Icons Fix** For Dropbox & Redshift *by [@mank319](https://github.com/mank319/elementaryPlus)*
```
add-apt-repository ppa:cybre/elementaryplus
apt update
apt upgrade && apt install elementaryplus
```

<br />

- [x] **Redshift*** **Icons** *by [@tobias-kuendig](https://gist.github.com/tobias-kuendig/d055892720cf09ae1a9d82075fb0f408)*
```
wget https://gist.github.com/tobias-kuendig/d055892720cf09ae1a9d82075fb0f408/raw/5d3625e5f4ac7686d7b40880a211ee72f74ea3d3/redshift-status-off.svg -O /tmp/redshift-status-off.svg
wget https://gist.github.com/tobias-kuendig/d055892720cf09ae1a9d82075fb0f408/raw/5d3625e5f4ac7686d7b40880a211ee72f74ea3d3/redshift-status-on.svg -O /tmp/redshift-status-on.svg

cp /tmp/redshift-status-off.svg /usr/share/icons/hicolor/scalable/apps/redshift-status-off.svg

cp /tmp/redshift-status-on.svg /usr/share/icons/hicolor/scalable/apps/redshift-status-on.svg

rm -f /tmp/redshift-status-o*.svg

killall redshift-gtk
```

<br />

### Redshift Configuration

* Copy *redshift.conf* to `Home/.config` folder [CTRL + H]

My configuration [redshift.conf](https://gist.github.com/suberb/6d52e55dd86245ce89bf8ddbfa2eb89c).


---

<br />

## OTHER

<br />

- [x] **Fix Lag** When OS Starts *by [@Jason Waddington](https://elementaryos.stackexchange.com/questions/7897/significant-lag-loading-panel-and-dock-after-login-loki)*

* Rename `/etc/xdg/autostart/at-spi-dbus-bus.desktop` and `/usr/share/upstart/xdg/autostart/at-spi-dbus-bus.desktop` files to `at-spi-dbus-bus.disabled`.
```
mv /etc/xdg/autostart/at-spi-dbus-bus.desktop /etc/xdg/autostart/at-spi-dbus-bus.disabled
mv /usr/share/upstart/xdg/autostart/at-spi-dbus-bus.desktop /usr/share/upstart/xdg/autostart/at-spi-dbus-bus.disabled
```

<br />

- [x] **Display Hidden Startup Applications**
```
sed -i 's/NoDisplay=true/NoDisplay=false/g' /etc/xdg/autostart/*.desktop
```

<br />

- [x] **PowerTop*** Recommended to use INSTEAD of TLP, not alongside.
```
apt update
apt install powertop -y
powertop --auto-tune
```
**Call** `powertop --auto-tune` **at boot:**

* **Option 1** *by [@Milosz Galazka](https://blog.sleeplessbeastie.eu/2015/08/10/how-to-set-all-tunable-powertop-options-at-system-boot/)*
```
cat << EOF | tee /etc/systemd/system/powertop.service
[Unit]
Description=PowerTOP auto tune

[Service]
Type=idle
Environment="TERM=dumb"
ExecStart=/usr/sbin/powertop --auto-tune

[Install]
WantedBy=multi-user.target
EOF
```
```
systemctl daemon-reload
systemctl enable powertop.service
```

* **Option 2**

Put `powertop --auto-tune` in `/etc/rc.local` file, before `exit 0`.

---

<br />

### Fix Desktop entries not executing
https://elementaryos.stackexchange.com/questions/10952/how-to-execute-desktop-in-files

## Features

- **Night light**
- **Hot Corner**

## THE LOOK




- [x] **elementaryOS Icon** Instead of "Applications" Text in Wingpanel


**The icon shows up behind the Network icon in Lock Screen. I don't know how to fix this.**

* Navigate to your main theme folder, for e.g.: `/usr/share/themes/elementary/`.
* Place your icon (preferably in **.svg** format) in the main theme folder. Here's [mine](https://www.dropbox.com/s/1v1xrgxdn50pv35/elementaryOS.svg?dl=0).
* Edit all `apps.css` files placed in GTK folders:
```css
/*********
 * Panel *
 ********/

.panel {
    background-color: transparent;
    background-image: url("../elementaryOS.svg");
    background-repeat: no-repeat;
    transition: all 100ms ease-in-out;
}

.panel .menubar:first-child {
    font-size: 0px;
    padding-left: 12px; /* If you're bothered by the Slingshot's skewed arrow */
}
```
```
killall wingpanel
```

- [x] **Always on Numlock:**

Don’t want to press the “Numlock” button every time you restart the PC? Well, the good thing about opensource is your imagination is the limitation. Open file manager as root, go to /usr/share/lightdm/lightdm.conf.d/40-io.elementary.greeter.conf.  
Open the file with your favorite text editor and paste “greeter-setup-script=/usr/bin/numlockx on” at the last.  
That’s it. You don’t have to think about Numlock again!

---

<br />

# BIG THANKS to:
* [@memoryleakx](https://gist.github.com/memoryleakx/7567474)
* [@evertontrindade](https://gist.github.com/evertontrindade/ef9214bb0558c149a5e502eea297f322)

<br />

:tada: