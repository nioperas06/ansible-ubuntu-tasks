# Simple Ansible Development VM to boot your Ubuntu server and perform basic administrative tasks.
> Things You MUST DO After Installing Ubuntu Server

This project aims to make spinning up a Linux server, create a new user and secure the server.
It should take 2-5 minutes to build or rebuild the VM from scratch on a decent broadband connection.

## Quick Start Guide

### 1 - Install dependencies (VirtualBox, Vagrant, Ansible)

  1. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).
  2. Download and install [Vagrant](http://www.vagrantup.com/downloads.html).
  3. [Mac/Linux only] Install [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

Note for Windows users: *This guide assumes you're on a Mac or Linux host. Windows hosts are unsupported at this time.*

### 2 - Build the Virtual Machine

  1. Download this project and put it wherever you want.
  2. Open Terminal, cd to this directory.
  4. Type in `vagrant up`, and let Vagrant do its magic.

Note: *If there are any errors during the course of running `vagrant up`, and it drops you back to your command prompt, just run `vagrant provision` to continue building the VM from where you left off. If there are still errors after doing this a few times, post an issue to this project's issue queue on GitHub with the error.*

## Notes

  - To shut down the virtual machine, enter `vagrant halt` in the Terminal in the same folder that has the `Vagrantfile`. To destroy it completely (if you want to save a little disk space, or want to rebuild it from scratch with `vagrant up` again), type in `vagrant destroy`.
