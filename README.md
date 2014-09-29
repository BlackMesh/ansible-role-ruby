ansible-role-ruby
=====================

Ansible Role to Install ruby from source

Currently only tested on CentOS.

## Requirements

None.

## Role Variables

ruby_ver: "2.1.2"
ruby_archive: ftp://ftp.ruby-lang.org/pub/ruby/2.1/ruby-{{ ruby_ver }}.tar.gz

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
        - { role: ruby }

## License

MIT / BSD

## Author Information

This role was created in 2014 by Solomon S. Gifford (sgifford@blackmesh.com) and sponsored by BlackMesh, Inc.

Credit: Inspired by https://github.com/akishin/ansible-playbooks
