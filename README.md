vagrant
=======

[Josh Benham](http://joshbenham.net)'s personal Vagrant script

Overview
--------

Vagrant script that I use to spawn a ubuntu virtual machine for web development

Instructions
------------
```sh
# grab the repo
$ git clone https://github.com/joshbenham/vagrant.git

# go into the directory
$ cd vagrant

# run the script (Make sure Vagrant is installed)
$ vagrant up

# ssh into vagrant
$ vagrant ssh

# update the system and install the lamp server
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install lamp-server^
```
