timezone
=========

[![Build Status](https://travis-ci.org/lborguetti/ansible-role-system-timezone.svg?branch=master)](https://travis-ci.org/lborguetti/ansible-role-system-timezone)

Ansible role for setting timezone and localtime.

Requirements
------------

Nothing.

Role Variables
--------------

        timezone_location: America/Sao_Paulo

This variable define your timezone and localtime.

Default values see defaults/main.yml

Dependencies
------------

Nothing.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lborguetti.system-timezone, system_timezone_location: "America/Sao_Paulo" }

License
-------

BSD

Author Information
------------------

[Luciano Antonio Borguetti Faustino](https://github.com/lborguetti)
