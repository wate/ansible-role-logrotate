logrotate
=================

configure logrotate

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `logrotate_settings`

logrotateの設定

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
