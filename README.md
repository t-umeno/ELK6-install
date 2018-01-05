# ELK6-install
install ELK6 on ubuntu/xenial64 (VirtualBox, Vagrant, Ansible)

## requirements
* VirtualBox
* Vagrant
* Ansible ( >= 2.2)
* vagrant plugin install vagrant-disksize
## Usage
    vagrant plugin install vagrant-disksize
    cd playbooks
    vagrant up
    ansible-playbook ELK6-install.yml
