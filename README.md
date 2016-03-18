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
|--------------------|------------------------------------------------------------------|--------------------------------|
| rabbitmq_version   | 3.6.1                                                            | Version of RabbitMQ to install |
| rabbitmq_sha256sum | 0728fbdb14ec62712c6f931a7d91648cafbc6c30d8d4da790832e784b4d2e956 | SHA 256 sum of package         |

Dependencies
------------

- kbrebanov.erlang

Example Playbook
----------------

Install RabbitMQ
```
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
