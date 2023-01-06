logrotate
=================

configure logrotate

OS Platform
-----------------

### Debian

- bullseye
- buster

Role Variables
--------------

### `logrotate_packages`

インストールするパッケージ

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: logrotate
```

License
--------------

Apache License 2.0
