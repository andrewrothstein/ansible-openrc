andrewrothstein.openrc
=========
![Build Status](https://github.com/andrewrothstein/ansible-openrc/actions/workflows/build.yml/badge.svg)

Creates [Open-RC](https://en.wikipedia.org/wiki/OpenRC) service definitions. Heavily inspired by [this](http://www.lexicallyscoped.com/2013/04/02/simple-init.d-script-for-ansible.html).

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
    - andrewrothstein.openrc
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
Fredrik Dyrkell <fredrik.dyrkell@gmail.com>
