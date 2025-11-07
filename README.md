# ansible-apps_postfix

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_postfix-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_postfix)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_postfix.svg)](https://github.com/lotusnoir/ansible-apps_postfix/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_postfix?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_postfix)
[![downloads](https://img.shields.io/ansible/role/d/56097)](https://galaxy.ansible.com/lotusnoir/apps_postfix)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56097)](https://galaxy.ansible.com/lotusnoir/apps_postfix)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Description](#description)
- [Requirements](#requirements)
- [Role variables](#role-variables)
- [Examples](#examples)
- [License](#license)
- [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Deploy postfix and use it as relay host through mailjet.

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_postfix
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_postfix

## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
