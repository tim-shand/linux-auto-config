# Linux Automated Configuration

The purpose of this project is to apply a "Configuration-as-Code" approach to both workstations and servers.  
Configuration changes, including package installation/removal, are driven by Ansible playbooks, targeting `roles` to assign the required settings.  

## Features

- Detects operating system version for use with distribution specific tools/commands.
- Automates package installation and removals based on pre-defined lists.
- Configures desktop environment and application settings (workstations).

## Usage

```bash
# Execute locally. 
sudo ansible-playbook local.yaml -i hosts

# Pull from Git repo.
ansible-pull -U https://github.com/tim-shand/linux-auto-config.git
```
