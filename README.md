revenni.docker
=========

Ansible role providing standalone docker deployment of Docker CE from official repos.

docker-compose also installed.

[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)
[![Platforms](http://img.shields.io/badge/platforms-debian-lightgrey.svg?style=flat)](#)
[![Licence](https://img.shields.io/badge/Licence-MIT-blue.svg)](https://tldrlegal.com/license/mit-license)

Requirements
------------

* None

Role Variables
--------------

* None

Dependencies
------------

* None

Example Playbook
----------------

    - hosts: all
      become: true
      roles:
         - { role: revenni.docker, tags: revenni.docker }

License
-------

MIT

Changelog
---------
10/10/2020 v1.0.1 Fixed ansible var to reflect distribution
06/14/2020 v1.0.0 First release, debian/ubuntu docker base


Author Information
------------------
* [Vince Hillier](https://revenni.com) | [@email](mailto:vince@revenni.com) | [twitter](https://twitter.com/vincedotca)
