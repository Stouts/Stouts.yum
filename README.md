Stouts.yum
===========

[![Build Status](http://img.shields.io/travis/Stouts/Stouts.yum.svg?style=flat-square)](https://travis-ci.org/Stouts/Stouts.yum)
[![Galaxy](http://img.shields.io/badge/galaxy-Stouts.yum-blue.svg?style=flat-square)](https://galaxy.yum.com/list#/roles/842)
[![Tag](http://img.shields.io/github/tag/Stouts/Stouts.yum.svg?style=flat-square)]()

Ansible role which manage sudoers file

#### Variables
```yaml
yum_enabled: yes                               # Enable role
```

#### Usage

Add `Stouts.yum` to your roles and set vars in your playbook file.

Example:

```yaml

- hosts: all

  roles:
    - Stouts.yum

```

#### License

Licensed under the MIT License. See the LICENSE file for details.

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Stouts/Stouts.yum/issues)!

