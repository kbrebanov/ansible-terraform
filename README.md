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
| terraform_version   | 0.6.7                                                            | Version of Terraform to install |
| terraform_sha256sum | 2e5de08f545e117eb9825b697c5ad290ee3fdcaae7d6de4b0e99830e58b38b2e | SHA 256 checksum of package     |

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
