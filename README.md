# Ansible LEMP
This ansible-playbook is used to deploy a LEMP environment on CentOS7/RetHat7;

## Requirements
* CentOS7/RetHat7 minimal install;

## Coverage
* check if OS is compatible and install yum-utils
* install nginx repository (Provided by Nginx) and certify the latest package was installed
* install mariadb repository (Provided by MariaDB) and certify the latest package was installed. Version could be configured at hosts
* install php repostiroy (Provided by Remi) and install php-fpm packages and other configurable at hosts. Version could be configured at hosts
## Configuration
* Some confs could be changed at inventory/hosts
* At ansible.cfg has only the local inventory conf;

## Consider
**Advice:** This project was created just to maintain my ansible-playbooks. You would be able to use, distribute, change or whatever you want, and don't need to mention myself. But use at your own risk. I can't guarantee that will be functional in your environment.

**Contact:** if you have any question or sugestion you can open an issue and I will response as soon as possible.