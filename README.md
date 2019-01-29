andrewrothstein.alpine-openrc
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-alpine-openrc.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-alpine-openrc)

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
    - andrewrothstein.alpine-openrc
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
Fredrik Dyrkell <fredrik.dyrkell@gmail.com>
