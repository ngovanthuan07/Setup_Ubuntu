## PHP

https://launchpad.net/~ondrej/+archive/ubuntu/php

```sudo add-apt-repository ppa:ondrej/php```
```sudo apt update```
```
sudo apt install php8.2-cli  php8.2-dev php8.2-pgsql php8.2-sqlite3 php8.2-gd php8.2-imagick \
  php8.2-curl php8.2-imap php8.2-mysql php8.2-mbstring php8.2-xml php8.2-zip \
  php8.2-bcmath php8.2-soap php8.2-intl php8.2-readline php8.2-ldap php8.2-msgpack \
  php8.2-igbinary php8.2-redis php8.2-memcache php8.2-pcov php8.2-xdebug php8.2-common php8.2-fpm
```
```php -v```

show module php: ``php -m``

## Composer
```
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === 'e21205b207c3ff031906575712edab6f13eb0b361f2085f1f1237b7126d785e826a450292b6cfd1d64d92e6563bbde02') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
```
```sudo mv composer.phar /usr/local/bin/composer```

``composer -v``
  
## LARAVEL
```composer global require laravel/installer```

## MySQL

```sudo apt install mysql-server```

sudo mysql -u root

#> MySQL command
```drop user root@localhost;```
```create user root@'%' identified with mysql_native_password by '';```
```grant all privileges on *.* to root@'%' with grant option;```
```flush privileges;```
