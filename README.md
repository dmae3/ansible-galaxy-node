Role of installing Node.js
=========

node ansible galaxy role.

Requirements
------------

None

Role Variables
--------------

* node_version  
Install nodejs version

* node_nodesource_download_url  
NodeSource rpm download url

* node_update_npm_enabled  
Update npm task

Dependencies
------------

None

Example Playbook
----------------

```yml
---
- hosts: all
  become: true
  roles:
    - { role: node, node_version: 6.9.1, node_nodesource_download_url: 'https://rpm.nodesource.com/pub_6.x/el/7/x86_64/nodesource-release-el7-1.noarch.rpm' }
```

License
-------

BSD

Author Information
------------------

[Daisuke Maeda](https://github.com/dmae3 "Daisuke Maeda")
