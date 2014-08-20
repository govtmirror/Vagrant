Vagrant
=======

This repository is used to store assorted Virtual Machines in the form of a Vagrantfile.

Dependencies
============

Vagrant

VirtualBox

Usage
=======
Assuming that the dependencies are installed, open a terminal (terminal, windows power shell, iterm, etc.) and:

* Clone this repository using the standard github method [git pull](http://git-scm.com/book/en/Git-Basics-Getting-a-Git-Repository#Cloning-an-Existing-Repository)
* Navigate (`cd`) into the directory with the Vagrantfile for the VM you wish to use.
* Run `vagrant up`

If the vagrant box is already installed on your computer, the machine will boot, provision (if requested), and be ready for use.  If the box is not already installed, it will first be downloaded from the internet.

Contributing a VM
==================
To contirbute a VM:

* Fork this project to your own github account
* Clone your fork local
* Add a new directory with a name representative of the VM
* Create and test a Vagrantfile (`vagrant init`)[https://docs.vagrantup.com/v2/getting-started/] 
  * Provision (using a script, Puppet, Chef, etc.) if required
* Push the changes to your forked repository
* Create a pull request into this repository

Note:
All VMs should use a box from a trusted source, e.g. [Vagrant Cloud](https://vagrantcloud.com/discover/featured).
