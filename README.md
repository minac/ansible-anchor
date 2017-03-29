
Ansible Anchor
=========

A deployment of anchor CMS with Ansible and Vagrant.


Requirements
------------

N/A


Role Variables
--------------

In vars/main.yml you can find two variables:

- mysql_user
- mysql_password
- mysql_user_home
- anchor_version: "0.12.1"


Dependencies
------------

N/A


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      become: true
      roles:
         - { role: minac.ansible-anchor }


License
-------

BSD


Author Information
------------------

Miguel David - migueldavid.eu
