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
| terraform_version   | 0.6.8                                                            | Version of Terraform to install |
| terraform_sha256sum | fd61718820c3f2334276517a89694cebe82db354b584ea90c376f1c6d34bb92d | SHA 256 checksum of package     |

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
