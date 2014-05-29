vagrant-mongodb
===============

MongoDB in a Vagrant VM

What You'll need
================

1. Vagrant
2. VirtualBox
3. Disk space and memory for a VM

Usage
=====

vagrant up, just like any other Vagrant setup.

Notes
=====

I've used the 'chef/fedora-20' box, because that's what I had to hand. Fork and change if you need, it should work with any RHL / Centos / Fedora.

It uses Puppet to install the tools.

Port mapping is done in the Vagrantfile.

Anything in the ./data folder isn't committed to Git, so the VM should stay small and can be readily destroyed at will (although I've not yet tested this...)

