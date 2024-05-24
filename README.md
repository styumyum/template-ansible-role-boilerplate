Template Ansible Role Boilerplate
=================================

Use this template as the base of Ansible roles.

Templating Variables
--------------------

Search for field with `<< xxx >>` and replace with your values.

Supported Versions
------------------

| Package | Version |
| ---- | ---- |
| ansible | 9.6.0 |
| molecule | 24.2.1 |
| molecule-plugins[openstack] | 23.5.3 |

Ansible role README file structure
----------------------------------

Include the below section in your Ansible role README.md:
````
ansible-role-xxx
================

# Description of your Ansible role.

Requirements
------------

**None**

Role Variables
--------------

**None**

Example Playbook
----------------

```
- hosts: all
  become: true
  roles:
    - role: ansible-role-xxx
      vars:
        disable_root_login: true
```
````