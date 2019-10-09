Role Name: engine-ldap
=========

[![Build Status](https://travis-ci.org/jobcespedes/engine-ldap.svg?branch=master)](https://travis-ci.org/jobcespedes/engine-ldap) [![Buy me a coffee](https://img.shields.io/badge/$-BuyMeACoffee-blue.svg)](https://www.buymeacoffee.com/jobcespedes)

Configure ldap auth in oVirt Engine

Requirements
------------

- Engine installed
- Package: `ovirt-engine-extension-aaa-ldap-setup`

Role Variables
--------------

- Define an `ovirt_engine_ldap_setup` dictionary
- See [`defaults/main.yml`](defaults/main.yml).

Dependencies
------------

- Depends on other Ansible roles: no

Example Playbook
----------------

```yaml
- hosts: engine
  roles:
    - jobcespedes.engine-ldap
```

License
-------

MIT

Author Information
------------------

Job Céspedes: jobcespedes@gmail.com
