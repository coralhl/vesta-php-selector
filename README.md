# VestaCP PHP Multi Selector, PHP 5.6, 7.0, 7.1, 7.2, 7.3, 7.4, 8.0, 8.1, 8.2
Vestacp, multi selector versions of php 5.6, 7.0, 7.1, 7.2, 7.3, 7.4, 8.0, 8.1, 8.2 for Ubuntu (Debian).

It has been tested and works on Ubuntu 20.04 and Debian 11, 12.

<h4>Discussion</h4>
https://forum.vestacp.com/viewtopic.php?f=41&t=20571

## vst-php-selector
This will work like cgi, fcgi or fpm.

You can use one of three scripts for your missions.

0) <h3>get it</h3>
```bash
git clone https://github.com/coralhl/vesta-php-selector.git
```

1) <h3>cgi</h3>
```bash
chmod a+x ./vst-php-cgi.sh
sudo ./vst-php-cgi.sh
```

2) <h3>fcgi</h3>
```bash
chmod a+x ./vst-php-fcgid.sh
sudo ./vst-php-fcgid.sh
```

3) <h3>fpm</h3>
```bash
chmod a+x ./vst-php-fpm.sh
sudo ./vst-php-fpm.sh
```

After running the script, you should choose the versions of php for example (7.2 7.4)
Script add repository and install chosen base versions of php.
Then you should install extensions rof example
```bash
$ sudo apt install php7.2-curl 
$ sudo apt install php7.4-curl
```
or
```bash
$ sudo apt install php7.0-apcu php7.0-mbstring php7.0-bcmath php7.0-cli php7.0-curl php7.0-gd php7.0-intl php7.0-mcrypt php7.0-mysql php7.0-soap php7.0-xml php7.0-xmlrpc php7.0-json php7.0-zip php7.0-memcache php7.0-memcached php7.0-ldap 
$ sudo apt install php7.1-apcu php7.1-mbstring php7.1-bcmath php7.1-cli php7.1-curl php7.1-gd php7.1-intl php7.1-mcrypt php7.1-mysql php7.1-soap php7.1-xml php7.1-xmlrpc php7.1-json php7.1-zip php7.1-memcache php7.1-memcached php7.1-ldap 
$ sudo apt install php7.2-apcu php7.2-mbstring php7.2-bcmath php7.2-cli php7.2-curl php7.2-gd php7.2-intl php7.2-mcrypt php7.2-mysql php7.2-soap php7.2-xml php7.2-xmlrpc php7.2-json php7.2-zip php7.2-memcache php7.2-memcached php7.2-ldap 
$ sudo apt install php7.3-apcu php7.3-mbstring php7.3-bcmath php7.3-cli php7.3-curl php7.3-gd php7.3-intl php7.3-mcrypt php7.3-mysql php7.3-soap php7.3-xml php7.3-xmlrpc php7.3-json php7.3-zip php7.3-memcache php7.3-memcached php7.3-ldap 
$ sudo apt install php7.4-apcu php7.4-mbstring php7.4-bcmath php7.4-cli php7.4-curl php7.4-gd php7.4-intl php7.4-mcrypt php7.4-mysql php7.4-soap php7.4-xml php7.4-xmlrpc php7.4-json php7.4-zip php7.4-memcache php7.4-memcached php7.4-ldap 
$ sudo apt install php8.0-apcu php8.0-mbstring php8.0-bcmath php8.0-cli php8.0-curl php8.0-gd php8.0-intl php8.0-mcrypt php8.0-mysql php8.0-soap php8.0-xml php8.0-xmlrpc php8.0-json php8.0-zip php8.0-memcache php8.0-memcached php8.0-ldap 
$ sudo apt install php8.1-apcu php8.1-mbstring php8.1-bcmath php8.1-cli php8.1-curl php8.1-gd php8.1-intl php8.1-mcrypt php8.1-mysql php8.1-soap php8.1-xml php8.1-xmlrpc php8.1-json php8.1-zip php8.1-memcache php8.1-memcached php8.1-ldap 
$ sudo apt install php8.2-apcu php8.2-mbstring php8.2-bcmath php8.2-cli php8.2-curl php8.2-gd php8.2-intl php8.2-mcrypt php8.2-mysql php8.2-soap php8.2-xml php8.2-xmlrpc php8.2-json php8.2-zip php8.2-memcache php8.2-memcached php8.2-ldap 
```

For old version of Ubuntu

```bash
$ sudo apt-get install php5.6-apcu php5.6-mbstring php5.6-bcmath php5.6-cli php5.6-curl php5.6-gd php5.6-intl php5.6-mcrypt php5.6-mysql php5.6-soap php5.6-xml php5.6-xmlrpc php5.6-json php5.6-zip php5.6-memcache php5.6-memcached php5.6-ldap 

```

Screenshots
------------
![1](/screenshot/php_version.png )
![2](/screenshot/php.png )