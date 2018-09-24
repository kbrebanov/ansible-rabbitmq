[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

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
| rabbitmq_version   | 3.6.10                                                           | Version of RabbitMQ to install |
| rabbitmq_sha256sum | 7b23114de13fb4bfd8c962c6d9f915f3d692c3c6623ca122c3abd5d4980d772b | SHA 256 sum of package         |

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
