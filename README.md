Fail2Ban
========

Install and Configure Fail2Ban on CentOS and Debian

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

```
- { role: rvalente.iptables }
```

Example Playbook
----------------

```
- hosts: servers
  roles:
    - { role: rvalente.fail2ban }

License
-------

See `LICENSE`

Author Information
------------------

Ronald Valente
