Role Caddy
=========

An Ansible Role that installs Caddy on Linux.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

    caddy_package: caddy
    caddy_package_state: present


Dependencies
------------
None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - nvjacobo.caddy
