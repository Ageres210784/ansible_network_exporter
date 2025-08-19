# ageres210784/network_exporter

An Ansible role which installs and configures [network_exporter] on docker container

## Requirements


Ansible 2.8+

## Role Variables


You can see all vars in `defaults/main.yml` vars file.

## Dependencies


None

## Example Playbook


```yaml
- name: Ensure network_exporter
  hosts: exporters
  remote_user: root

  roles:
    - ageres210784.network_exporter
```

## License


Apache 2.0

## Author Information


This role was created by [Sergey Evseev].
