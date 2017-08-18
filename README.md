ansible-forpsi-vmtoolsd
=========

This role removes old preinstalled VMware tools from forpsi VM and installs open-vm-tools from EPEL repository

Requirements
------------

There is not any prerequisities to use this role

Role Variables
--------------

    vmtoolsd_uninstall_script

Specifies path to Perl uninstall script for preinstalled VMware tools.

Dependencies
------------

There is not any depencencies

Example Playbook
----------------

    - hosts: forpsi
      roles:
         - ansible-forpsi-vmtoolsd

License
-------

BSD

Author Information
------------------

Jakub Slatinsky, slatinskyj@gmail.com
