# Ansible Role: acme_sh

[![Lint](https://github.com/dcjulian29/ansible-role-acme_sh/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-acme_sh/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-acme_sh.svg)](https://github.com/dcjulian29/ansible-role-acme_sh/issues)

This an Ansible role to install acme.sh to issue and renew Let's Encrypt SSL certificates

## Requirements

- Internet Connection to download acme.sh script.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.acme_sh
  src: https://github.com/dcjulian29/ansible-role-acme_sh.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
