[![Build Status](https://travis-ci.org/thomaslorentsen/ansible-sudo.svg?branch=master)](https://travis-ci.org/thomaslorentsen/ansible-sudo)
# Ansible Sudo
Configure sudo

# Usage
```yaml
  - thomaslorentsen.ansible-sudo
```
Add group to specified users
```yaml
  - {role: thomaslorentsen.ansible-sudo, sudo_users: [travis]}
```
