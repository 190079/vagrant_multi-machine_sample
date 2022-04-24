# vagrant_multi-machine_sample

## Description 
This is a vagrant file to set up a master node and two worker node of ubuntu generic 20.04.

## Requirements
1. Vagrant
2. libvirt/virtualbox (any one)

## Usage
If you are using kvm qemu as hypervision you can leave the vagrant setting to default, but if you want to use virtualbox as the hypervisior then comment out the following.
> VMM="libvirt"

> #VMM = "libvirt" 

After commenting the libvirt uncomment the following line.
> #VMM= "virtualbox"

> VMM = "libvirt"

### To run the vagrant file.
> vagrant up

### To destroy the box
> vagrant destroy

## Author 
__Alish Bista__
