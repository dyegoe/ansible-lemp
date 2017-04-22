# Ansible LEMP
This ansible-playbook is used to deploy a LEMP environment on CentOS7;

## Requirements
* CentOS7 minimal install;

## Coverage
* install nginx repository and certify the latest package was installed (role: nginx, tag: nginx)
* install mariadb (mysql)
## Configuration
* Some confs can be changed at inventory/hosts
* At ansible.cfg has only the local inventory conf;

## Consider
**Advice:** This project was created just to maintain my ansible-playbooks. You can use, distribute, change or whatever you want, and don't need to mention myself. But use at your own risk. I can't guarantee that will be functional in your environment.

**Contact:** if you have any question or sugestion you can open an issue and I will response as soon as possible.