============================================
VagrantFile to Bootstrap Opscode Chef Server
============================================

Guest OS
--------

* Ubuntu Server Precise 64 bit

Requirements
------------

* Git-core
* Vagrant
* Virtualbox

Install
-------

After cloning, run the following commands to grab the latest cookbooks

* $git submodule init
* $git submodule update

Then, run the following to provision the vagrant instance.

* $vagrant up


Vagrant: http://vagrantup.com/