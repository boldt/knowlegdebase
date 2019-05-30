# Fix boot error messages

## Check for boot error messages

```bash
journalctl -r -p3
```

## Cannot access vdagent virtio channel /dev/virtio-ports/com.redhat.spice.0

```bash
sudo apt purge spice-vdagent
```

* https://askubuntu.com/questions/1126260/is-spice-vdagent-required-for-wayland/1126397
* https://forums.fedoraforum.org/showthread.php?310792-vdagent-message-via-journalctl-occurs-alot

## Assuming drive cache: write through

```
Mai 27 00:16:02 denpc kernel: sd 8:0:0:0: [sdd] Assuming drive cache: write through
Mai 27 00:16:02 denpc kernel: sd 8:0:0:0: [sdd] No Caching mode page found
```

```bash
sudo update-pciids && sudo update-usbids
sudo dpkg --configure -a
```

*NOTE*: Not working.

* https://askubuntu.com/questions/32107/how-to-avoid-assuming-drive-cache-write-through-message-during-restart
* https://ubuntuforums.org/showthread.php?t=1475788
