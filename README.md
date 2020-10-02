ansible-role-basic
=========

Install common dependencies for other ansible roles

Requirements
------------

- Sudo permission

Role Variables
--------------

Dependencies
------------

No dependencies

Example Playbook
----------------

```
---
- name: Playbook
  hosts: localhost
  connection: local
  roles:
    - ansible-role-basic
```

License
-------

MIT
