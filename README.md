ansible-role-basic
=========

Install common dependencies for other ansible roles and optionally yay as AUR wrapper tool

Requirements
------------

- Sudo permission

Role Variables
--------------

- `yay`: set to true to install [yay](https://github.com/Jguer/yay)

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
