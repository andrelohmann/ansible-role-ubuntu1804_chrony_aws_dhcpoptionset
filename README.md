ubuntu1804_chrony_aws_dhcpoptionset
===================================

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-ubuntu1804_chrony_aws_dhcpoptionset.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-ubuntu1804_chrony_aws_dhcpoptionset)

Use this role, to allow the configuration of the chrony ntp client on Ubuntu 18.04, to be able to set its ntp servers by a dhcp lease.


Requirements
------------

This role requires ubuntu.

Example Playbook
----------------

    - hosts: ubuntu1804_chrony_aws_dhcpoptionset
      roles:
         - andrelohmann.ubuntu1804_chrony_aws_dhcpoptionset

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
