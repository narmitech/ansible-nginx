## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) nginx

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-nginx.svg?style=flat)](https://travis-ci.org/debops/ansible-nginx)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--nginx-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-nginx/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.nginx-660198.svg?style=flat)](https://galaxy.ansible.com/debops/nginx)


The [nginx](https://nginx.org/) is a fast and light webserver with extensible
configuration.

The `debops.nginx` role can be used to install and manage `nginx` configuration
for multiple websites at the same time. The server is configured using
inventory variables. This role can also be used as a dependency of another role
to configure a webserver for that role using dependency variables.

### Installation

This role requires at least Ansible `v2.0.0`. To install it, run:

```Shell
ansible-galaxy install debops.nginx
```

### Role dependencies

- `debops.secret`
- `debops.apt_preferences`
- `debops.ferm`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Maciej Delmanowski](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-drybjed) (maintainer) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)
- [Robin Schneider](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-ypid) | [e-mail](mailto:ypid@riseup.net) | [GitHub](https://github.com/ypid)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
