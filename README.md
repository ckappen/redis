redis [![Build Status](https://travis-ci.org/ckappen/redis.svg?branch=master)](https://travis-ci.org/ckappen/redis)
=========

This role helps to deploy a Redis server on target host.

Requirements
------------

This role requires Ansible 2.3 or higher (it's made with 2.3.1), and platform requirements are listed in `meta/main.yml`

Role Variables
--------------

All role variables can be found in `defaults/main.yml`

Dependencies
------------

All role dependencies can be found in `meta/main.yml`

Test Playbook
-------------

If you want to know what is tested through [molecule](https://molecule.readthedocs.io/en/master/) see:

- `molecule.yml` for OSes we test against
- `playbook.yml` for what is being run in the test
- `tests/test_default.yml` for the [goss](https://goss.rocks) verfier

Contribute
----------

http://kbroman.github.io/github_tutorial/pages/fork.html

Author Information
------------------

Christian Kappen (https://github.com/ckappen)
