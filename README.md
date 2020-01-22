# Ansible Role: ElasticSearch

[![Build Status](https://travis-ci.org/lordoftheflies/ansible-role-elasticsearch.svg?branch=master)](https://travis-ci.org/lordoftheflies/ansible-role-elasticsearch)
[![Travis CI](http://img.shields.io/travis/lordoftheflies/ansible-role-elasticsearch/default.svg?style=flat)](http://travis-ci.org/lordoftheflies/ansible-role-elasticsearch/default)
[![pipeline status](https://gitlab.cherubits.hu/oss/ansible-galaxy-roles/ansible-role-elasticsearch/badges/master/pipeline.svg)](https://gitlab.cherubits.hu/oss/ansible-galaxy-roles/ansible-role-elasticsearch/commits/master)
[![coverage report](https://gitlab.cherubits.hu/oss/ansible-galaxy-roles/ansible-role-elasticsearch/badges/master/coverage.svg)](https://gitlab.cherubits.hu/oss/ansible-galaxy-roles/ansible-role-elasticsearch/commits/master)
[![Platforms](http://img.shields.io/badge/platforms-debian%20/%20ubuntu-orange.svg?style=flat)](#)

## Description

[Ansible Galaxy](https://galaxy.ansible.com/) role for [ElasticSearch](https://www.elastic.co/products/elasticsearch).

## Boards

* [ROADMAP](https://gitlab.cherubits.hu/oss/ansible-galaxy-roles/ansible-role-elasticsearch/-/boards/97)
* [DEVELOPMENT](https://gitlab.cherubits.hu/oss/ansible-galaxy-roles/ansible-role-elasticsearch/-/boards/98)
* [VERIFICATION](https://gitlab.cherubits.hu/oss/ansible-galaxy-roles/ansible-role-elasticsearch/-/boards/99)

## Requirements

* [Python 3.4+](https://python.io/)

### Production

* [Ansible](https://ansible.com/)

### For Local Testing

* [Vagrant](https://www.vagrantup.com/) - (Tested using version 2.1.1)
* Vagrant plugins:
  * [vagrant-plugin-disksize (0.1.2)](https://github.com/lordoftheflies/vagrant-plugin-disksize)
  * [vagrant-plugin-vbguest (0.15.2)](https://github.com/lordoftheflies/vagrant-plugin-vbguest)
  * vai (0.9.3) - For testing with multiple vms [vagrant-plugin-vai](https://github.com/lordoftheflies/vagrant-plugin-vai) 
* [Virtual Box](https://www.virtualbox.org/)
  * Tested using Version 5.2.14 r123301 (Qt5.6.1) 

## Variables

### defaults/main.yml

* [defaults/main.yml](defaults/main.yml) contains all of the required variables.

### Example

* [ansible-role-elasticsearch.yml](files/site.yml) may contain an example entry.

## Testing

To test with all VM's defined in Vagrantfile run the following:

```shell
cd ansible-role-elasticsearch
vagrant up
```

To run on a specific VM's
```shell
vagrant up xenial
```

### VM's tested with Vagrant and Virtualbox

pass, fail, untested

| Distribution | Results  |
| ------------ | -------- |
| precise      | untested |
| trusty       | untested |
| xenial       | untested |
| bionic       | untested |
| CentOS 6     | untested |
| CentOS 7     | untested |

## Authors and License

- [László Hegedűs](mailto:laszlo.hegedus@cherubits.hu)

License: [Apache-2.0](LICENSE)

> **NOTE**: ansible-role-elasticsearch generated using [galaxy-role-skeleton](https://github.com/cjsteel/galaxy-role-skeleton)
