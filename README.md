# Setting up PPA on Ubuntu

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
         - agoloncser.ubuntu_ppa

## License

BSD

## Author Information

https://github.com/agoloncser
