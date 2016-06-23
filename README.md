# Philosophy
The philosophy of the rhtps projects

## Background
A solutions architecture team within Red Hat's Public Sector group saw recurring problems with disconnected installs of Red Hat software. By disconnected, we mean any of the following scenarios:

* A fully air-gapped network
* A network with a restrictive security policy
* A network with a proxy that replaces valid SSL certificates

These repos are to help make disconnected installs easier and more repetable.

## Design goals
If you have written something that makes disconnected installs easier, we'd love to include it! These are the design goals we're striving towards:

* Everything has to work without Internet access
  * An exception to this is tools that enable other disconnected tools such as our [rhtps.yum](https://github.com/rhtps/ansible-yum) and [rhtps.registry](https://github.com/rhtps/ansible-registry) Ansible roles
* Wherever possible, use Ansible
* When using Ansible, everything has to be role-based and follow documented [best practices](http://docs.ansible.com/ansible/playbooks_best_practices.html)

## Ansible Galaxy
Our Ansible roles can be located on our [Ansible Galaxy page](https://galaxy.ansible.com/rhtps).

## What does the name mean?
Offically, nothing. But if you're curious, it comes from Red Hat's stock symbol (RHT) and PS for Public Sector.
