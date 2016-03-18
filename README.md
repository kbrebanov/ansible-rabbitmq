rabbitmq
========

[![Ansible Role](https://img.shields.io/ansible/role/5474.svg)](https://galaxy.ansible.com/list#/roles/5474)

Installs RabbitMQ

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name               | Default                                                          | Description                    |
|--------------------|------------------------------------------------------------------|--------------------------------|
| rabbitmq_version   | 3.5.6                                                            | Version of RabbitMQ to install |
| rabbitmq_sha256sum | e3c377e585c123e06c88422248915f32216641d6f7dfab50d124535c8e93010d | SHA 256 sum of package         |

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
