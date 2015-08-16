# Vagrant/Ansible Bootstrap
This is just a handy repo to create new ansible/vagrant projects from.

#####It contains my default:
- ```Vagrantfile``` which auto generates the ```envs/vagrants.hosts``` file based on the contents of the ```vagrant-servers.yml``` file.
- ```vagrant-servers.yml``` which allows you to define ansible roles and the servers they contain
- ```.gitignore``` which just has some basic ignores/contains
- ```scripts/env-ansible.sh``` which is just a handy script to run ansible playbooks by including ```<project>.hosts```, ```<project>.config```, ```<project>.secret``` files
- ```roles/base-linux``` which is an ansible role to perform some basic initial linux configuration.
