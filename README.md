Role Name
=========

A simple role to setup a host as a git server

Requirements
------------

NA

Role Variables
--------------

```

Variable                                Level       Description                                                         

git_user                                Default     The git os user
git_pass                                Default     The git os user password
git_repo_path                           Default     The directory where the git repos will be stored


```


Dependencies
------------

NA

Example Playbook
----------------

```
---
- hosts: git_server
  become: yes
  roles:
    - { role: infra_server_git_setup } 
```   

License
-------

BSD

Author Information
------------------

Petros Petrou - ppetrou@gmail.com
