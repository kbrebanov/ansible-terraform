terraform
=========

[![Ansible Role](https://img.shields.io/ansible/role/6256.svg)](https://galaxy.ansible.com/list#/roles/6256)

Installs Terraform

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name                | Default                                                          | Description                     |
|---------------------|------------------------------------------------------------------|---------------------------------|
| terraform_version   | 0.6.9                                                            | Version of Terraform to install |
| terraform_sha256sum | c7d3e76de165be9f47eff8f54b41bb873f6f1881d2fb778a54bb8aaf69abfae6 | SHA 256 checksum of package     |

Dependencies
------------

- kbrebanov.unzip

Example Playbook
----------------

Install Terraform
```
- hosts: all
  roles:
    - kbrebanov.terraform
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
