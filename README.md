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
