# Gnome

## Tweak tool

```bash
apt install gnome-tweaks
```

## Allow installation from browser

```bash
sudo apt-get install chrome-gnome-shell
```

Install browser extension: https://extensions.gnome.org/local/

### Configure Workspaces

* https://extensions.gnome.org/extension/484/workspace-grid/

```bash
gnome-tweaks
```

* Workspaces
    * Static workspaces: 4
 
* Extentions -> Workspace grid -> gear symbol
    * Rows: 1
    * Colums: 1

### Icons on desktop

* Desktop
    * Disbale "Trash"
    * Disbale "Mounted Volumes"

* http://ubuntuhandbook.org/index.php/2018/04/remove-trash-icon-ubuntu-18-04-desktop/

## Themes

* Default
    * Applications: Ambiance
    * Mouse: DMZ-White
    * Symbols: Ubuntu-mono-dark
    * Shell: Warning

### Install

```bash
sudo apt install arc-theme
```

* Applications -> Select "Arc-Dark"

### Install from gnome-look.org

* Download:
    * https://www.gnome-look.org/p/1214931/
    * Flat-Remix-GTK-Blue-Darker_2.20.tar.xz
    * Unzip

```bash
sudo mv path-of-theme /usr/share/themes
```

* http://www.linuxandubuntu.com/installing-themes-in-linux.html
* https://www.howtogeek.com/358049/how-to-install-desktop-themes-on-ubuntu-18.04-lts/

### Activities Configurator

* https://extensions.gnome.org/extension/358/activities-configurator/
    * Hide Text
    * Change logo to: /usr/share/icons/Humanity/places/64/start-here.svg
    * Disbale "hot corner"
    * Transparncy top line: 70%
* https://kofler.info/desktop-konfiguration-fuer-ubuntu-18-04/


### System Monitor

```bash
apt install gir1.2-gtop-2.0 gir1.2-networkmanager-1.0 gir1.2-clutter-1.0
```

* https://extensions.gnome.org/extension/120/system-monitor/
