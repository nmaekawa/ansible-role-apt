apt
=========
Simple ansible role to upgrade (full or safe[default]), install a
list of required packages (defauts: [python-apt, unattended-upgrades]), and
purge list of unwanted packages (defaults: none).


requirements
------------

A Debian-based system with `apt` installed.



example playbook
----------------

    - hosts: all
      roles:
         - { role: ansible-role-apt, apt_required_packages: ['htop'], apt_other_packages }

license
-------

Apache2


credits
-------

* https://github.com/conorsch/ansible-role-update-everything.git
* https://github.com/ANXS/apt.git

