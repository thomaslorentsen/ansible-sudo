# Ansible Sudo
Configure sudo

# Usage
```yaml
  - {role: ansible-sudo}
```
Add group to specified users
```yaml
  - {role: ansible-sudo, sudo_users: [travis]}
```
