Purpose of this Vagrant/Ansible combi is to 

1. have a working setup of provisioning a Vagrant VM with Ansible
2. test the Ansible playbook to install Spark on a CentOS

I followed the guide provided by Vagrant: https://www.vagrantup.com/docs/provisioning/ansible.html

### Prerequisites

* Virtual Box: `brew cask install virtualbox`
* Vagrant: `brew cask install vagrant`

### Get Started

Run `vagrant up --provision` to create a CentOS VM and provision it with Ansible, i.e. install Spark on it.
