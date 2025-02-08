dnscache
========
[![Ansible Lint](https://github.com/oxivanisher/role-dnscache/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-dnscache/actions/workflows/ansible-lint.yml)

Installs the `nscd` package on Debian based distros.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Debian clients
  hosts: debian
  roles:
    - role: oxivanisher.linux_base.dnscache
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_base](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_base/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_base).
