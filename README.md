Ansible Role: Apache
=========

Installs and configures the [Apache HTTP Server](https://httpd.apache.org/)

WIP Notice
----------

This role is a Work-In-Progress. It is limited in the following ways:

* Simply installs and does just enough configuration to run
* Currently, only CentOS7 is supported

Requirements
------------

None

Role Variables
--------------

TBD

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: apache }

License
-------

CC0

Author Information
------------------

Drew Heles
