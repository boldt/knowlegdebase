# Pdftk

## Define coreect driver

```bash
lspci -nnk | grep -i vga -A3 | grep 'Subsystem'
```

> `Subsystem: CardExpert Technology GK104 [GeForce GTX 760] [10b0:1187]`

Open: https://www.nvidia.de/Download/index.aspx?lang=de

> `Version: 430.14`

## Check driver

```bash
lspci -nnk | grep -i vga -A3 | grep 'in use'
sudo lshw -c video | grep driver
```

## Install

```bash
sudo add-apt-repository ppa:graphics-drivers/ppa
sudo apt update
sudo apt install nvidia-driver-430 nvidia-settings
```

## Source

* https://askubuntu.com/a/1075757/217106
* https://askubuntu.com/questions/524242/how-to-find-out-which-nvidia-gpu-i-have
* https://askubuntu.com/questions/770092/is-it-a-good-idea-to-install-nvidia-361-drivers-in-14-04
* http://ubuntuhandbook.org/index.php/2019/04/nvidia-430-09-gtx-1650-support/
* https://www.nvidia.com/object/unix.html


