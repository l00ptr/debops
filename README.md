## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) dnsmasq

[![Travis CI](http://img.shields.io/travis/debops/ansible-dnsmasq.svg?style=flat)](http://travis-ci.org/debops/ansible-dnsmasq) [![test-suite](http://img.shields.io/badge/test--suite-ansible--dnsmasq-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-dnsmasq/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.dnsmasq-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1561)
### Warning, this is a BETA role

This role has been marked by the author as a beta role, which means that it
might be significantly changed in the future. Be careful while using this role
in a production environment.

***

This role installs and configures `dnsmasq` as a local DNS, DHCP and
PXE/TFTP server. At the moment configuration is limited, and resulting
environment is suited for local development only. A NATted network can also
be configured for ease of use for local virtual machines / LXC containers
without the need for additional external IP addresses.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.dnsmasq

### Documentation

More information about `debops.dnsmasq` can be found in the
[official debops.dnsmasq documentation](http://docs.debops.org/en/latest/ansible/roles/debops.dnsmasq.html).


### Role dependencies

- `debops.ferm`
- `debops.tcpwrappers`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`dnsmasq` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
