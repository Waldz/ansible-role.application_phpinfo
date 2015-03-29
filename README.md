# ansible-role.application_phpinfo

Install
========
```
git submodule add git@github.com:Waldz/ansible-role.application_phpinfo.git roles/application_phpinfo
```

Example
========
```
- name: Deploy basic tools to all servers
  hosts: all
  sudo: true
  roles:
    #- role: nginx
    - role: application_phpinfo
```

Variables
========
group_vars/all.yml
```
---
phpinfo_path_public: /var/www/default/php
```
