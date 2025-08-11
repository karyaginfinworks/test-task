# Ansible Server Setup Project


## 📋 Description

Comprehensive Ansible project for automating server setup and optimization in enterprise infrastructure. Ensures security, performance, and reliability of critical systems.


### Prerequisites
- Ansible 2.12+ (recommended 2.18+)
- Python 3.8+
- SSH access to target servers
- Sudo privileges on target servers

### Installation
```bash
# Clone project
git clone <repository-url>
cd ansible-server-setup

# Install Ansible (if not installed)
apt install ansible

# Install necessary collections
ansible-galaxy collection install     ansible.posix     community.general     community.crypto     community.docker     ansible.utils     community.network     --force

# Check installation
ansible --version
```



### Server setup
```bash
# Setup all components
ansible-playbook -i inventory.yml all.yml

# With additional debugging
ansible-playbook -i inventory.yml all.yml  -v
```
