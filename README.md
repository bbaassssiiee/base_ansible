=========

base_python is a role to install python in the context of Ansible (Tower). 
It includes crypto extensions with compiled code.

Requirements
------------

RHEL-like, or Debian/Ubunto system


Role Variables
--------------

'ansible_rpms' is a list of packages for RedHat-like systems
'ansible_apts' is a list for Debian/Ubuntu

Dependencies
------------

- role: bbaassssiiee.base_cplusplus
- role: bbaassssiiee.base_python

Example Usage
----------------

Refer to a complete build server https://github.com/bbaassssiiee/buildserver

License
-------

MIT

Author Information
------------------

Bas Meijer
@bbaassssiiee
