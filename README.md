CloudStack
=========

Role to install and configure CloudStack Management host currently version 4.4

Tested on:
 - Ubuntu 14.04 LTS x64
 - ansible 1.8 (Installed from git clone)
 - MySQL 5.6.19

Requirements
------------
MySQL Host

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: cloudstackmgmt
  roles:
   - CloudStack
```

License
-------
GPLv3

Author Information
------------------

Tal Lannder

Tal@Pjili.com
