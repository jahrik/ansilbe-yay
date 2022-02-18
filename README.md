# Yay

Installs [yay](https://github.com/Jguer/yay)

## Requirements

- base-devel
- git

## Role Variables

Set to install or uninstall and cleanup

    install: true/false

## Dependencies

None

## Example Playbook

    - hosts: all
      roles:
         - { role: jahrik.yay, install: true }

## License

GPLv2

## Author Information

jahrik@gmail.com

https://homelab.business/
