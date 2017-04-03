[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-nettools.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-nettools)
andrewrothstein.nettools
===========================

A role for installing assorted network inspection command line tools

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.nettools
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
