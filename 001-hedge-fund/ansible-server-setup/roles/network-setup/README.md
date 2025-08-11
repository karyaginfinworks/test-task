# Network Setup Role

## Description

This role provides simple network interface renaming functionality for Ubuntu systems using netplan.


## Requirements
- Ansible 2.12+
- Ubuntu system with netplan
- Root or sudo access
- Active network connection


### Execute only this role
```bash
ansible-playbook -i inventory.yml all.yml --tags network-setup
```
