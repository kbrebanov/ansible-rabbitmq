rabbitmq
========

[![Ansible Role](https://img.shields.io/ansible/role/5474.svg)](https://galaxy.ansible.com/list#/roles/5474)

Installs RabbitMQ

Requirements
------------

None

Role Variables
--------------

| Name             | Default | Description                    |
|------------------|---------|--------------------------------|
| rabbitmq_version | 3.5.6   | Version of RabbitMQ to install |

Dependencies
------------

None

Example Playbook
----------------

Installl RabbitMQ
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
