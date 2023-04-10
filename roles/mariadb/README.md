MariaDB
=========

Instals and configures MariaDB.

Requirements
------------

A host to install MariaDB on.

Role Variables
--------------

A set of default variables is defined in defaults.
Distro specific variables are defined in vars.
The playbook's variable distro specifies the distro vars being used.

Dependencies
------------

None.

Example Playbook
----------------

time ansible-playbook playbook.yml
time ansible-playbook playbook.yml --tags configuration

License
-------

BSD
