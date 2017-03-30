# Ansible Role: CentOS Kernel Update
[![GitHub Open Issues](https://img.shields.io/github/issues/pozgo/ansible-role-centos-kernel-update.svg)](https://github.com/pozgo/ansible-role-centos-kernel-update/issues)
[![GitHub Stars](https://img.shields.io/github/stars/pozgo/ansible-role-centos-kernel-update.svg)](https://github.com/pozgo/ansible-role-centos-kernel-update)
[![GitHub Forks](https://img.shields.io/github/forks/pozgo/ansible-role-centos-kernel-update.svg)](https://github.com/pozgo/ansible-role-centos-kernel-update)
[![GitHub release](https://img.shields.io/github/release/pozgo/ansible-role-centos-kernel-update.svg)](https://github.com/pozgo/ansible-role-centos-kernel-update)
[![license](https://img.shields.io/github/license/pozgo/ansible-role-centos-kernel-update.svg?maxAge=2592000)](https://github.com/pozgo/ansible-role-centos-kernel-update/blob/master/LICENSE)

---

Ansible role updates CentOS kernel to the latest version.

### Requirements

### Example Playbook

    - hosts: servers
      roles:
         - { role: pozgo.centos-kernel-update, tags: ['update'] }

---
### Author

Author: Przemyslaw Ozgo (<linux@ozgo.info>)
