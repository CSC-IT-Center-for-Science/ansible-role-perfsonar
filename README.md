ansible-role-perfsonar
=========

Configures perfsonar after installation

Requirements
------------

A machine where base image of persfonar is installed.

Role Variables
--------------

a few variables need to be set for this to work:

 - adminMailAddr
 - trusted_public_networks (space separated string of trusted networks)
 - trusted_public_ipv6_networks (space separated string of trusted networks)
 - nagios_allowed_hosts: (comma separated string)
 - nagios_allowed_hosts_ipv6: (comma separated string)


Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-perfsonar }

License
-------

MIT

Author Information
------------------
