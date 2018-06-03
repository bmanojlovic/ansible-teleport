ansible-teleport
=========

Simple ansible role to install and configure teleport ssh service

Requirements
------------

Linux server :)

Role Variables
--------------

This roles provides a lot of settable variables, please look at defaults/main.yml for all of them, sensible default should work on debian and suse/redhat distributions

Dependencies
------------

No dependencies for now

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: teleport_hosts
      roles:
         - { role: bmanojlovic.ansible-teleport, teleport_version: 2.6.1 }

License
-------

BSD
