Role Name
=========

Installs common yum packages on all my EL6 hosts.

Requirements
------------

None

Role Variables
--------------

The following are the variables used in this role

defaults/main.yml:
devpkgs: a list of development packages to install.
epel_url: the URL for the EPEL repository package to install.
pkgs: a list of the common packages to install.

Dependencies
------------

None

Example Playbook
----------------

An example playbook to test this role.

    - hosts: servers
      roles:
         - { role: ansbile-common-yum-pkgs-el6 }

License
-------

BSD

Author Information
------------------

Abubakr-Sadik Nii Nai Davis
https://github.com/ttousai
@ttousai
