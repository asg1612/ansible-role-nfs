Role Name
=========

Install NFS server on Centos or Ubuntu

Requirements
------------

None

Role Variables
--------------
- **path_export**: path for export nfs data
- **network**: list of networks to allow access. ej: 192.168.1.1/24


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: asg1612.nfs-server }

License
-------

BSD

Author Information
------------------

This role was created in 2017 by [Andrés Sáncher García](http://andressaga.es/)
