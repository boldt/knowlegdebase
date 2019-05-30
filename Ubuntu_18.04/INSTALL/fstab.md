# Mount HDDs on startup

```bash
gnome-disks
```

* This modifies `/etc/fstab`


## Get User id and group id for HDDs with NFFS

```bash
id -u dennis
> 1000

id -g dennis
> 1000
```

Append `gid=1000,uid=1000` to the corresponding HDD

