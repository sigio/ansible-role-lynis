Lynis
=====

An Ansible role to install Lynis (on Debian/Ubuntu/RHEL/CentOS/etc) which installes the lynis version from the cisofy.com repositories, with support for installing the enterprise/commercial add-ons.

Requirements
------------

A supported OS (currently debian/ubuntu/redhat/centos)

Role Variables
--------------

Define the 'lynis_license_key' value if using the commercial/enterprise version or leave this undefined or false to use the community edition.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: sigio.lynis }

License
-------

BSD

Author Information
------------------

Mark Janssen <info@sig-io.nl>
Sig-I/O Automatisering
