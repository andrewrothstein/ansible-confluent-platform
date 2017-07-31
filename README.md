andrewrothstein.confluent-platform
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-confluent-platform.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-confluent-platform)

Installs the [Confluent OSS Platform](https://www.confluent.io/product/confluent-open-source/).

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
    - andrewrothstein.confluent-platform
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
