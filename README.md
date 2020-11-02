# Ansible Role: NewRelic

[![Build Status](https://travis-ci.com/davidalger/ansible-role-newrelic.svg?branch=master)](https://travis-ci.com/davidalger/ansible-role-newrelic)

Installs the NewRelic APM and NewRelic Infrastructure agents on EL 7/8.

## Requirements

None.

## Role Variables

See `defaults/main.yml` for details.

## Dependencies

None.

## Example Playbook

    - hosts: web-servers
      vars:
        newrelic_license: YOUR_NR_LICENSE_KEY_HERE

      roles:
        - { role: davidalger.newrelic, tags: newrelic }

## License

This work is licensed under the MIT license. See LICENSE file for details.

## Author Information

This role was created in 2017 by [David Alger](http://davidalger.com/).
