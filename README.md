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
| rabbitmq_version   | 3.6.5                                                            | Version of RabbitMQ to install |
| rabbitmq_sha256sum | 9de570ca9e3d30bdc26a79c683503e158d35e5cacafb36e4e9b01d73929bf5a9 | SHA 256 sum of package         |

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
