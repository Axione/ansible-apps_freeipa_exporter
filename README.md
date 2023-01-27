# ansible-apps_freeipa_exporter

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_freeipa_exporter-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_freeipa_exporter)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_freeipa_exporter.svg)](https://github.com/lotusnoir/ansible-apps_freeipa_exporter/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_freeipa_exporter?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_freeipa_exporter)
[![downloads](https://img.shields.io/ansible/role/d/56085)](https://galaxy.ansible.com/lotusnoir/apps_freeipa_exporter)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56085)](https://galaxy.ansible.com/lotusnoir/apps_freeipa_exporter)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Deploy [freeipa_exporter](https://github.com/boynux/freeipa-exporter) to expose freeipa metrics to prometheus.

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_freeipa_exporter
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_freeipa_exporter


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

