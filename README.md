Web-Stack Deployment with Ansible
===========================

This Ansible Role deploys on hetzgate
* `Deploys complete site
* `Auto git pull`

Requirements
------------

* Currently only tested with CentOS 7
* Ansible 2.4 or higher is required for this Ansible Role
* Previously run melvin_suter.hetzgate role

Role Variables
--------------

Variables are self speaking or documented in:   
* `defaults/main.yml`

Dependencies
------------

This Ansilbe Role has dependencies to these Ansilbe Roles:
* `uniqconsulting.mariadb`

Example Playbook
----------------

Example playbooks for this role are located in ´test´ folder:
* `tests/playbook_webstack.yml`
