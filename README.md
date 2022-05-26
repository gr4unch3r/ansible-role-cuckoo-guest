# Ansible Role Cuckoo Guest

[![CI](https://github.com/gr4unch3r/ansible-role-cuckoo-guest/actions/workflows/ci.yml/badge.svg)](https://github.com/gr4unch3r/ansible-role-cuckoo-guest/actions/workflows/ci.yml)

Ansible role to provision a [Cuckoo Sandbox](https://cuckoosandbox.org/) guest.

## Requirements

- Windows 10 VM configured for remoting with Ansible (e.g. [gr4unch3r/windows-10](https://app.vagrantup.com/gr4unch3r/boxes/windows-10))
- [ansible.windows](https://galaxy.ansible.com/ansible/windows)
- [community.windows](https://galaxy.ansible.com/community/windows)
- [chocolatey.chocolatey](https://galaxy.ansible.com/chocolatey/chocolatey)

## Example Playbook

```
- hosts: all
  roles:
    - gr4unch3r.cuckoo_guest
```

## License

MIT

## Author Information

gr4unch3r [at] protonmail [dot] com
