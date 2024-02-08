# Setting up PPA on Ubuntu

[![Molecule testing](https://github.com/agl4/ansible-role-ubuntu-ppa/actions/workflows/ci.yml/badge.svg)](https://github.com/agl4/ansible-role-ubuntu-ppa/actions/workflows/ci.yml)

This role sets up PPA properly ready for installing packages from there.

## Requirements

None.

## Role Variables

### `ubuntu_ppa_repositories`

If defined (as a list) also configures the repositories.

## Dependencies

None.

## Example Playbook

    - hosts: localhost
      vars:
        ubuntu_ppa_repositories:
          - ppa:fish-shell/release-3
      roles:
         - agl4.ubuntu_ppa

## License

BSD

## Author Information

[@agl4](https://github.com/agl4)
