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
    
    1) Login in terminal with "Vagrant up"
    
    2) Go to root "cd /var/www"

    3) Run build script "sudo ./bin/db-build"

## URI's

By utilizing the hostmanager vagrant plugin the follwing URL's will be used by default

##Public URL's
    
    [http://wdev.base] (http://wdev.base 'http://wdev.base')
    [phpmoadmin] (http://phpmoadmin.base 'http://phpmoadmin.base')
    
  
##Private URI's
    
    Private network: 192.168.56.101
    Root directory /var/www
    Docroot /var/www/public
    PHPmoAdmin root /var/www/phpmoadmin

## Databases
    
By default this machine comes with the following database

    database: webdevbase
    user: webdevbase
    password: 1234