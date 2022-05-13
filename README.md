# pi-dns-homeserver
Ansible setup of Raspberry Pi DNS server (PiHole with Unbound).

## Prerequisites
Need a Raspberry Pi or other Ubuntu compatible hardware.
Start with a fresh Ubuntu install.

## Installation
Installation is quick and easy:
- Install Ubuntu
- Run the following commands (ssh or interactively)
```
sudo apt install git ansible
git clone https://github.com/fhug/pi-dns-homeserver.git
cd pi-dns-homeserver/ansible
// udpate the variables in the ./vars/init_vars.yml file as required 
ansible-playbook setup_playbook.yml -K
```
***Dont forget to update the init_vars file as required.***
