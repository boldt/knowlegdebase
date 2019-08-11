# Brackets

**HINT**: Brackets conflics with curl:

* brackets needs libcurl3
* curl needs libcurl4

Thus, we install from a PPA:

## Install from PPA

```
sudo add-apt-repository ppa:webupd8team/brackets
sudo apt-get update
sudo apt-get install brackets
```

## Install from DEB

Download *.deb from: http://brackets.io/

```bash
sudo apt install libcurl3
sudo apt install ./Brackets*.deb 
```
