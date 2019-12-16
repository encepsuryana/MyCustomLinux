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
	
	**MAC THEMES**
	- [x] **Sheel Theme** [McMojave](https://www.gnome-look.org/p/1275087/) || [McOS-Theme CTLina](https://www.gnome-look.org/p/1241688/)
	- [x] **Icon** [McMojave-cricle](https://www.gnome-look.org/s/Gnome/p/1305429) || [Mojave CT icons](https://www.gnome-look.org/s/Gnome/p/1210856) || [OS Catalina ](https://www.gnome-look.org/s/Gnome/p/1309810)
	- [x] **Cursor** [ Capitaine Cursors](https://www.gnome-look.org/p/1148692/)

	**Installation**
	- [x] Extract All Download file 
	- [x] Open Terminal on main location extraction
	- [x] use command `sudo mv /folder-themes /usr/share/themes` for install themes
	- [x] use command `sudo mv /folder-icons /usr/share/icons` for install icons
	- [x] use command `sudo mv /folder-cursors /usr/share/icons` for install cursors
	- [x] and than open tweaks application, on tab `Aplication` change the gnome-shel, cursor and aplications

- [x] **Plank and disable ubuntu Docks**
	disable Dock Ubuntu
	```bash
	gsettings set org.gnome.shell.extensions.dash-to-dock intellihide false
	```

	Install Plank
	```bash
	sudo apt install plank -y
	```
---

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
- [x] **Tusk** *Unofficial Evernote For Linux* [sourceforge.net/projects/nevernote/files/?source=navbar](https://sourceforge.net/projects/nevernote/files/?source=navbar)

- [x] **Sublime Text**
- [x] **Sublime Merge**
- [x] **WPS Office*** [wps-community.org/downloads](http://wps-community.org/downloads) *Check WPS Fonts Fix*

---

:tada: