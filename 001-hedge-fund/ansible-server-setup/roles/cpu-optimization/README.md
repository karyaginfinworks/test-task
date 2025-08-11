# CPU-optimization Role

## Description
Role for CPU performance optimization on enterprise servers. Configures CPU governor, disables C-states for latency minimization, and optimizes Intel Hyper-Threading and AMD SMT parameters for high-performance applications.

## Requirements
- Ansible 2.12+
- Sudo privileges on target host
- Intel or AMD processor with frequency scaling support
- Packages `cpufrequtils` and `linux-tools-common` (installed automatically)


### Execute only this role
```bash
ansible-playbook -i inventory.yml all.yml --tags cpu-optimization
```
