rabbitmq
========

[![Build Status](https://travis-ci.org/kbrebanov/ansible-rabbitmq.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-rabbitmq)

Installs and configures RabbitMQ.

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name               | Default                                                          | Description                    |
|:-------------------|:-----------------------------------------------------------------|:-------------------------------|
| rabbitmq_version   | 3.6.2                                                            | Version of RabbitMQ to install |
| rabbitmq_sha256sum | 87217c0b135c6705f1d9ac2fcdbc355eeb3b0f53562c4f430e79861b0b7057b8 | SHA 256 sum of package         |

Dependencies
------------

- kbrebanov.erlang

Example Playbook
----------------

Install RabbitMQ
```yaml
- hosts: all
  roles:
    - kbrebanov.rabbitmq
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
