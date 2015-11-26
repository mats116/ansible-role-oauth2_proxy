# README.md
# Ansible Role: mats116.oauth2_proxy

An Ansible role that installs [oauth2_proxy](https://github.com/bitly/oauth2_proxy) on **Ubuntu 14.04 LTS**

## Requirements

none

## Role Variables

Available variables are listed below, along with default values:

```yaml
oauth2_proxy_version: "2.0.1"

oauth2_proxy_http_address: 127.0.0.1:4180
```

## Dependencies

none

## Example Playbook

```yaml
- hosts: proxy-server
  roles:
    - role: mats116.oauth2_proxy
      oauth2_proxy_http_address: 0.0.0.0:4180
```

## License

MIT
