# System-info Role

## Description
Role for collecting and displaying detailed system information on enterprise servers. Analyzes CPU characteristics, memory, network, disks and creates comprehensive reports for infrastructure monitoring and optimization.

## Requirements
- Ansible 2.12+
- Sudo privileges on target host (for some commands)
- Utilities `lscpu`, `dmidecode`, `ethtool` (usually pre-installed)



### Execute only this role
```bash
ansible-playbook -i inventory.yml all.yml --tags system-info
```
