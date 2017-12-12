VerosK.firewalld
================

Setup firewalld and put services there.
Role Variables
--------------

Check `defaults/main.yml`

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: VerosK.firewalld
           firewalld_enabled_services: 
                 - https
                 - http
           firewalld_disabled_services:
                 - memcached
                 - redis
            

License
-------

BSD

<!-- Author Information
------------------ -->

