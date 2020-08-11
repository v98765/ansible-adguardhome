Ansible Role: adguardhome
=========

Deploy [AdGuardHome](https://github.com/AdguardTeam/AdGuardHome) DNS.

Requirements
------------

Ansible

Role Variables
--------------

All variables which can be overridden are stored in defaults/main.yml

`adguard_dir: /home/adguard`

Example Playbook
----------------

```text
---
- hosts: home
  connection: ssh
  become: yes
  roles: 
    - ansible-adguardhome

```

License
-------

BSD
