# Disk-encryption Role

## Description
Role for automatic disk encryption using LUKS (Linux Unified Key Setup). Provides secure data storage on enterprise servers with support for automatic mounting of encrypted partitions.

## Requirements
- Ansible 2.12+
- Sudo privileges on target host
- `cryptsetup` package (installed automatically)
- Unencrypted block disk for encryption


### Execute only this role
```bash
ansible-playbook -i inventory.yml all.yml --tags disk-encryption
```

