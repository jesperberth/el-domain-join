el-domain-join
=========

Domain Join Enterprise Linux servers

Requirements
------------


Role Variables
--------------

*  ad_server_user - username for admin
*  ad_server_pass - password for admin
*  ad_server_domain - domain name

´´´bash

---
ad_server_user: Administrator
ad_server_pass: Your Password
ad_server_domain: domain.local

´´´´

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
         - jesperberth.el-domain-join

License
-------

BSD

Author Information
------------------

Jesper Berth
