# Keepass2

## Install Keepass 2

```bash
sudo add-apt-repository ppa:jtaylor/keepass
sudo apt-get update
sudo apt-get install keepass2
```

## Install KeePassRPC.plgx

Download the newest `KeePassRPC.plgx` from:

* https://github.com/kee-org/keepassrpc/releases/tag/v1.9.0

Move the plugin to `/usr/lib/keepass2/Plugins`:

```bash
sudo mv KeePassRPC.plgx /usr/lib/keepass2/Plugins
```

*HINT*: Restart Keepass2

## Install Thunderbrid plugin (Keebird)

```bash
sudo apt-add-repository ppa:dlech/keepass2-plugins
sudo apt-get update
sudo apt-get install xul-ext-keebird
```

**HINT**: `xul-ext-keebird` installs an old version of `KeePassRPC.plgx`, thus remove the older one from the folder `plugins`-folder (lower case):

```bash
rm -rf /usr/lib/keepass2/plugins/KeePassRPC.plgx
```

* Restart Thunderbird Thunderbird: It asks to enter the auth code.
* Move in Thunderbird stored passwords to Keepass2 and delete them.

## Install Firefox plugin (Kee)

* Install the plugin from: https://addons.mozilla.org/de/firefox/addon/keefox/
* Restart Firefox: It asks to enter the auth code
* Move in Firefox stored passwords to Keepass2 and delete them.

## Sources

* http://ubuntuhandbook.org/index.php/2017/04/install-the-latest-keepass2-2-35-in-ubuntu-16-04-16-10-14-04/
* https://forum.kee.pm/t/installing-kee-with-keepassrpc-for-keepass-password-safe-instructions/23
* https://github.com/kee-org/KeeFox/wiki/en-%7C-Installation-%7C-Linux
* https://github.com/kee-org/keebird/wiki
