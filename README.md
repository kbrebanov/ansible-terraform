terraform
=========

[![Build Status](https://travis-ci.org/kbrebanov/ansible-terraform.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-terraform)

Installs Terraform

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name                | Default                                                          | Description                     |
|---------------------|------------------------------------------------------------------|---------------------------------|
| terraform_version   | 0.6.10                                                           | Version of Terraform to install |
| terraform_sha256sum | d7c07e2bf587257673bae710c776430a8cc5a755a9ad4a2cbae066d0cd02a862 | SHA 256 checksum of package     |

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
