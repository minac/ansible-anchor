
Ansible Anchor
=========

A deployment of Anchor CMS with Ansible and Vagrant.


Requirements
------------

N/A


Role Variables
--------------

In vars/main.yml you can find two variables:

- mysql_user
- mysql_password
- mysql_user_home
- anchor_version



Dependencies
------------

N/A


Example Playbook
----------------

```yaml
- hosts: all
  become: true
  roles:
     - { role: minac.anchor }
```


License
-------

BSD


Author Information
------------------

Miguel David - migueldavid.eu
