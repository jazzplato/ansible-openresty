ansible-openresty
=========

[![Build Status](https://travis-ci.org/jazzplato/ansible-openresty.svg?branch=master)](https://travis-ci.org/jazzplato/ansible-openresty)

A plain and simple role to install [OpenResty](https://openresty.org/en/) on Linux (currently only Ubuntu) after being tortured by the tedious command line installation for multiple times \_(:3」∠)\_

Requirements
------------

- Ansible: `2.1` or newer
- Ubuntu: `18.04` or newer

Role Variables
--------------

None, at least for the moment.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jazzplato.ansible-openresty }

License
-------

MIT

Author Information
------------------

> "Anyone saw my Tardis?", Richthofen whispers to himself.
