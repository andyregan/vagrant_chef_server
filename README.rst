============================================
VagrantFile to Bootstrap Opscode Chef Server
============================================

OS
--

Uses Ubuntu Precise 64

Install
-------

After cloning, run the following commands to grab the latest cookbooks

$git submodule init
$git submodule update

Then, run the following to provision the vagrant instance.

$vagrant up
