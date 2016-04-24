# ansible-playbooks
Bootstrapping sript for my laptop/pc


Setup

## Install Ansible Playbook
pip install ansible-playbook

## Register Ansible Hosts
At /etc/ansible/hosts

add:
[personal-machines]
localhost

[development-machines]
localhost

## Bootstrap command
ansible-playbook bootstrap.yml -K