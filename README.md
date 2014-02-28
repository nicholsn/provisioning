ansible-niquery
===============

This repository contains [ansible playbooks](http://docs.ansible.com/playbooks.html) to provision components of the niquery system architecture. The directory layout follows the [ansible best practices](http://docs.ansible.com/playbooks_best_practices.html).

Each of the [ansible roles](http://docs.ansible.com/playbooks_roles.html#roles) are designed to be reusable, as long as the common base role is installed.

The hosts file and top level yaml files (e.g., base.yml) are used to provision [docker contaiers](https://www.docker.io/learn_more/), but can also be used to provision any Ubuntu box with the same functionality as a container.

Currently the following hosts are available:

- base
- virtuoso
- niquery