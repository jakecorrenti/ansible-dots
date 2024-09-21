# ansible-dots

Dotfile management with Ansible playbooks

## Pre-requisites
**NOTE: Configure SSH and GPG keys for GitHub before starting**

Ensure that you have [Ansible installed](https://docs.ansible.com/ansible/2.9/installation_guide/intro_installation.html)
```bash
sudo dnf install ansible
```

Install the community collection of modules 
```bash
ansible-galaxy collection install community.general
```

## Running the playbook
To run the playbook and configure the development environment, run the following
```bash
ansible-playbook -K boostrap.yaml
```
