# Nmap

## Install

```bash
sudo apt-get install nmap
```

## Usage

### Get the Cipher suites for a mail server

```bash
nmap --script ssl-enum-ciphers -p 993 imap.example.com
```

### Get the Cipher suites for a web server

```bash
nmap --script ssl-enum-ciphers -p 443 www.example.com
```
