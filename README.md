### What is Vagrant?

Vagrant is a tool for building and managing virtual machine enviroment in a single workflow. Vagrant lowers development enviroment setup time, increase productivity.

## Why Vagrant?

- Easy to configure,
- Reproducible and portable work enviroment

## For Operators

Vagrant allows DevOps engineer a disposible enviroment and consisent workflow for developing and testing infracstracture managment scripts. Test things like Shell Scripts, Puppet modules.

## Basic Vagrant commands

vagrant init  = Vagrant file is a configuration file that describes the enviroment. It will incudle things like the boxes used, networking, CPU and memory provided

vagrant box - this command allows users to manage the boxes on their local machine, this includes adding, removing, listing and updating.

vagrant up - gets vagrant box up and running

vagrant ssh - gives the ability to connect to a particular box

vagrant destroy - destroys your enviroment. This can be used to test out configuration in a Vagrantfile. For example if a change has been made in a vagrant file and the outcome of it is not good. in order to get the enviroment back to a clean state, vagrant destroy can be used to wipe out all virual machines that vagrant was using.

### What is Ubuntu?

Ubuntu is derived from Debian Linux. Debian uses the dpkg packaging system. A package system is a way to provide programs and application for installation. This way you don't have to build a program from the source code.

APT is a command line tool to interact with this packaging system.

There are two main tools around APT: apt-get and apt-cache.apt-get is for insatlling, upgrading and cleaning packages.
#
## Basic command lines

sudo apt-get update - When you run this command you will see inormation being retrived from various servers

You will see 3 type of lines
- HIT - there is no change in the package version
- IGN - the package is being ignored
- get - There is a new version of the package available.


sudo apt-get upgrade - Once packages have been updated, you can upgrade the installed packages.
