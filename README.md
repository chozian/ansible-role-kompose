kompose
=========

This Ansible role is for installing and maintaining the kompose application on Linux.

Requirements
------------

* Ansible >= 2.11.0

* Linux Distribution

    * Red Hat Family

        * RHEL 7

    * Note: Other versions are likely to work, but have not been tested.

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD 3-Clause

Author Information
------------------

Chris Hozian  
Madison, AL, USA
