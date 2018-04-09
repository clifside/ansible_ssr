
[![Build Status](https://travis-ci.org/clifside/ansible_ssr.svg?branch=master)](https://travis-ci.org/clifside/ansible_ssr)

ansible_ssr
=========

Installs [ShadowsocksR](https://github.com/shadowsocksr-backup/shadowsocksr.git)

Requirements
------------

edit shadowsocks.json change the port&passwd settings

Role Variables
--------------

install path & ShadowsocksR version could be edited in defaults/main.yml and vars/main.yml

Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: Clifside.ansible_ssr }

License
-------

BSD

Author Information
------------------

Clifside gongzhen163@163.com


