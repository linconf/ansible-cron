# Ansible Role: cron

<!--
[![Build Status](https://travis-ci.org/linconf/ansible-cron.svg?branch=master)](https://travis-ci.org/linconf/ansible-cron)
[![Ansible Galaxy](https://img.shields.io/badge/docs-ansible--cron-blue.svg)](http://linconf.com/ansible-cron/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-linconf.cron-660198.svg)](https://galaxy.ansible.com/linconf/cron/)
-->

An Ansible role that manages cron jobs on Debian/Ubuntu and RHEL/CentOS.

## Installation

```
ansible-galaxy install linconf.cron
```

## Example Playbooks

**Add a Cron Job**

```
- hosts: localhost
  roles:
    - linconf.cron
  vars:
    cron:




```

See the [Ansible cron module](http://docs.ansible.com/ansible/cron_module.html) for a full list of available options.


**Remove a Cron Job**

```
cron:



```


**Additional Options**

See the [linconf.cron documentation](http://linconf.com/ansible-cron/) for a full list of available options.



## Dependencies / Requirements

- None

## Testing

The master branch is continuously validated by Travis-CI.

Minor versions indicate the role passed local testing as described by the
`.kitchen` declaration. Instructions for performing test-kitchen runs locally
are detailed in the [LinConf Documentation](http://linconf.com/about/methodology/).

## Author and License

Chad Sheets - [GitHub](https://github.com/cjsheets) | [Blog](http://chadsheets.com/) | [Email](mailto:chad@linconf.com)

Released under the [MIT License](https://tldrlegal.com/license/mit-license)

[![Analytics](https://cjs-beacon.appspot.com/UA-10006093-3/github/linconf/ansible-cron?pixel)](https://github.com/linconf/ansible-cron)
