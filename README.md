# taloLoggerGraph
Ansible role for installing olammi's taloLoggerGraph. Tested to work on Debian
squeeze (SPARC) and Raspbian (ARM) with latest ansible available from pip.

# Example playbook

```
---
- hosts: all
  sudo: yes
  roles:
    - taloLogger
    - taloLogger-role
```
