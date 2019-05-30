# Minimal vs. normal installation

* https://www.reddit.com/r/Ubuntu/comments/9f8o0d/minimal_vs_normal_installation/
* https://people.canonical.com/~ubuntu-archive/seeds/ubuntu.bionic/desktop.minimal-remove

## Minimal

* No updates on boot
* No additional driver

# Update and upgrade

```bash
sudo apt update
sudo apt upgrade
sudo apt dist-upgrade
```
# Install software

```bash
sudo apt-get install $(cat data/software-list)
```
