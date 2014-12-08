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
    

## URI's

By utilizing the hostmanager vagrant plugin the follwing URL's will be used by default

##Public URL's
    
    http://wdev.base 
    
  
##Private URI's
    
    Private network: 192.168.56.101
    Root directory /var/www
    Docroot /var/www/public

## Databases
    
By default this machine comes with the following database

    database: webdevbase
    user: webdevbase
    password: 1234