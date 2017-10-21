## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) dnsmasq

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-dnsmasq.svg?style=flat)](https://travis-ci.org/debops/ansible-dnsmasq)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--dnsmasq-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-dnsmasq/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.dnsmasq-660198.svg?style=flat)](https://galaxy.ansible.com/debops/dnsmasq)


This role installs and configures `dnsmasq` as a local DNS, DHCP and
PXE/TFTP server. You can use it to configure host-based LAN behind a bridge
interface for virtual machines / containers, or use it in your internal
network.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

```Shell
ansible-galaxy install debops.dnsmasq
```

### Documentation

More information about `debops.dnsmasq` can be found in the
[official debops.dnsmasq documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-dnsmasq/docs/).



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