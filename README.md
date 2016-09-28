Purpose of this Vagrant/Ansible combi is to 

1. have a working setup of provisioning a Vagrant VM with Ansible
2. test the Ansible playbook to install different packgages on a CentOS

For a list of different packages see [provisioning/roles/](./provisioning/roles/).

I followed the guide provided by Vagrant: https://www.vagrantup.com/docs/provisioning/ansible.html

### Prerequisites

* Virtual Box: `brew cask install virtualbox`
* Vagrant: `brew cask install vagrant`

### Get Started

Check [provisioning/playbook.yml](./provisioning/playbook.yml) which role is enabled to be installed on the VM.

Run `vagrant up --provision` to create a CentOS VM and provision it with Ansible, i.e. install e.g. Spark on it.

