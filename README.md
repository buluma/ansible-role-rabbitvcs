# [Ansible role rabbitvcs](#ansible-role-rabbitvcs)

Install and configure rabbitvcs on your system.

|GitHub|GitLab|Downloads|Version|
|------|------|---------|-------|
|[![github](https://github.com/buluma/ansible-role-rabbitvcs/workflows/Ansible%20Molecule/badge.svg)](https://github.com/buluma/ansible-role-rabbitvcs/actions)|[![gitlab](https://gitlab.com/shadowwalker/ansible-role-rabbitvcs/badges/master/pipeline.svg)](https://gitlab.com/shadowwalker/ansible-role-rabbitvcs)|[![downloads](https://img.shields.io/ansible/role/d/buluma/rabbitvcs)](https://galaxy.ansible.com/buluma/rabbitvcs)|[![Version](https://img.shields.io/github/release/buluma/ansible-role-rabbitvcs.svg)](https://github.com/buluma/ansible-role-rabbitvcs/releases/)|

## [Example Playbook](#example-playbook)

This example is taken from [`molecule/default/converge.yml`](https://github.com/buluma/ansible-role-rabbitvcs/blob/master/molecule/default/converge.yml) and is tested on each push, pull request and release.

```yaml
---
- name: Converge
  hosts: all
  become: yes
  gather_facts: yes

  roles:
    - role: buluma.rabbitvcs
```

The machine needs to be prepared. In CI this is done using [`molecule/default/prepare.yml`](https://github.com/buluma/ansible-role-rabbitvcs/blob/master/molecule/default/prepare.yml):

```yaml
---
- name: Prepare
  hosts: all
  become: yes
  gather_facts: no

  roles:
    - role: buluma.bootstrap
```

Also see a [full explanation and example](https://buluma.github.io/how-to-use-these-roles.html) on how to use these roles.


## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/buluma/ansible-role-rabbitvcs/blob/master/requirements.txt).

## [State of used roles](#state-of-used-roles)

The following roles are used to prepare a system. You can prepare your system in another way.

| Requirement | GitHub | GitLab |
|-------------|--------|--------|
|[buluma.bootstrap](https://galaxy.ansible.com/buluma/bootstrap)|[![Build Status GitHub](https://github.com/buluma/ansible-role-bootstrap/workflows/Ansible%20Molecule/badge.svg)](https://github.com/buluma/ansible-role-bootstrap/actions)|[![Build Status GitLab](https://gitlab.com/shadowwalker/ansible-role-bootstrap/badges/master/pipeline.svg)](https://gitlab.com/shadowwalker/ansible-role-bootstrap)|
|[buluma.ca_certificates](https://galaxy.ansible.com/buluma/ca_certificates)|[![Build Status GitHub](https://github.com/buluma/ansible-role-ca_certificates/workflows/Ansible%20Molecule/badge.svg)](https://github.com/buluma/ansible-role-ca_certificates/actions)|[![Build Status GitLab](https://gitlab.com/shadowwalker/ansible-role-ca_certificates/badges/master/pipeline.svg)](https://gitlab.com/shadowwalker/ansible-role-ca_certificates)|

## [Context](#context)

This role is part of many compatible roles. Have a look at [the documentation of these roles](https://buluma.github.io/) for further information.

Here is an overview of related roles:
![dependencies](https://raw.githubusercontent.com/buluma/ansible-role-rabbitvcs/png/requirements.png "Dependencies")

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://hub.docker.com/u/buluma):

|container|tags|
|---------|----|
|[Debian](https://hub.docker.com/r/buluma/debian)|all|
|[Ubuntu](https://hub.docker.com/r/buluma/ubuntu)|all|

The minimum version of Ansible required is 2.12, tests have been done on:

- The previous version.
- The current version.
- The development version.

If you find issues, please register them on [GitHub](https://github.com/buluma/ansible-role-rabbitvcs/issues).

## [License](#license)

[Apache-2.0](https://github.com/buluma/ansible-role-rabbitvcs/blob/master/LICENSE).

## [Author Information](#author-information)

[Michael Buluma](https://buluma.github.io/)

