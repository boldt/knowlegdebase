# LAMP-Server

## Install Apache

```bash
sudo apt -y install apache2
```bash

## Install PHP 7.2

```bash
sudo apt -y install php7.2 libapache2-mod-php7.2
```

## Restart

```bash
sudo systemctl restart apache2
```

## Test

Create phpinfo:

```bash
sudo nano /var/www/html/phpinfo.php
```

Add to `phpinfo.php`:

```php
<?php phpinfo(); ?>
```

Open:

* http://localhost/phpinfo.php

# Sources

* https://gridscale.io/community/tutorials/lamp-stack-auf-ubuntu-18-04-lts-mit-php-7-2-und-apache-2-4/
