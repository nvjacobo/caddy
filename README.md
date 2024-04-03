Role Caddy
=========

An Ansible Role that installs Caddy on Linux.

Requirements
------------

You need root privileges or sudo user to run this role.



Supported Operating Systems
------------
- Debian bullseye
- Debian bookworm


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
