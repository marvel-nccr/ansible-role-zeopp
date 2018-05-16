[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-zeopp.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-zeopp)

# Ansible Role: marvel-nccr.zeopp

An ansible role that installs [zeo++](http://www.zeoplusplus.org/) on Ubuntu.

## Installation

`ansible-galaxy install marvel-nccr.zeopp`

Note: This role looks for the files `zeopp_user` and `zeopp_pass` in the `./keys` folder (not provided) in order to download the zeo++ source code.

## Role Variables

See `defaults/main.yml`

## Example Playbook

  - hosts: servers
    roles:
    - role: marvel-nccr.zeopp

## License

MIT

## Contact

Please direct inquiries regarding Quantum Mobile and associated ansible roles to the [AiiDA mailinglist](http://www.aiida.net/mailing-list/).
