### wDevBase

### Vagrant Machine

## Prerequisites

To run this on your local computer you will need the following 2 programs installed.

1) [Virtualbox] (https://www.virtualbox.org "VirtualBox")

2) [Hostmnager] (https://github.com/smdahlen/vagrant-hostmanager#installation "Hostmanager installation")

 
## Install 

To install this machine please follow the bellow instructions

    1) git clone https://github.com/fwahlqvist/wdevbase

    2) cd wdevbase

    3) vagrant up

## Build Scripts

To build [phpmoadmin] (http://phpmoadmin.base) you will need to
    
    1) Login in with "vagrant ssh"
    
    2) Go to root "cd /var/www"

    3) Run build script "sudo ./bin/db-build"

## URI's

By utilizing the hostmanager vagrant plugin the follwing URL's will be used by default

##Public URL's
    
    http://wdev.base
    phpmoadmin
    
  
##Private URI's
    
    Private network: 192.168.56.101
    Root directory /var/www
    Docroot /var/www/webapp/public
    PHPmoAdmin root /var/www/phpmoadmin
    webapp /var/www/webapp

## Databases
    
By default this machine comes with the following Mongo database

    database: webdevbase
    user: webdevbase
    password: 1234

## ZFTool

To use ZFtool [read the documenation] (http://framework.zend.com/manual/2.3/en/modules/zendtool.introduction.html) or use the following command

    cd /var/www
    zftool.phar version
    zftool.phar create module module-name /var/www/webapp
    
## Development Mode

Once you have the basic installation, you need to put it in development mode:
    
    cd /var/www/webapp
    php public/index.php development enable # put webapp in development mode
