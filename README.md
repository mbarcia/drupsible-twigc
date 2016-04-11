drupsible.twigc
========================

Installs and configure the Twig C extension. 

Requirements
------------

This role requires PHP5 FPM (Fast Process Manager) to be present. 
This role can be used indepedently and does NOT require Drupsible to run.

Example Playbook
----------------

- name: twigc
  hosts: localhost
  become: True
  roles:
    - role: drupsible.twigc

License
-------

GNU General Public License v3

Author Information
------------------

Mariano Barcia - [https://github.com/mbarcia](https://github.com/mbarcia)
