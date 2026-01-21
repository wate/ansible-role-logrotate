logrotate
=================

configure logrotate

OS Platform
-----------------

### Debian

- trixie
- bookworm

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `logrotate_settings`

logrotateの設定  
@see https://hackers-high.com/linux/man-jp-logrotate/

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
