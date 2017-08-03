Role Name
=========

Install following programs
--------------------------

vim enhanced
wget
pip (latest)
yum-utils
libselinux-python
qpid-dispatch
device-mapper-persistenvirt-data
lvm2

Add following repositories
--------------------------

amq-interconnect for RHEL 6&7
amq-clients for RHEL 6&7
epel

Requirements
------------

None.


Usage
----------------

ansible-playbook -i <HOST_FILE> rh_server_main.yml


License
-------

Apache 2.0


Author Information
------------------

Messaging QE team @ redhat.com
