====================
ansible-role-ansible
====================

Ansible role to manage ansible

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-ansible.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-ansible
* Bugs: https://bugs.launchpad.net/ansible-role-ansible

Description
-----------

Ansible is the simplest way to automate apps and IT infrastructure.

Requirements
------------

* pip3 to be installed if using ansible_install_method: (git|pip)

See `bindep.txt` for role dependencies.

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install ansible
      hosts: foo
      roles:
        - ansible-role-ansible
