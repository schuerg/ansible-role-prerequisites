Ansible Role: Prerequisites
===========================

This is the ultimate prerequisites role needed for ansible provisioning.
It prepares the managed node for ansible tasks, e.g. it installs `python3` on the managed node via an ansible raw command.

This role is also published on [Ansible Galaxy](https://galaxy.ansible.com/schuerg/prerequisites/).

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: schuerg.prerequisites }

Feedback
--------

Bug reports, feature requests, pull requests and feedback in general is always welcome!

License
-------

[MIT](LICENSE)

Author Information
------------------

This role was created in 2016 by Simon Schürg.
