Role Name
=========

Deployment of zabbix-agent2 on Debian and RHEL

Requirements
------------

Nothing special

Role Variables
--------------

zabbix_serber: IP's of zabbix server agent will listen to.

zabbix_server_active: IP of Server zabbix will actively report to.


Example Playbook
----------------
    - hosts: servers
      
      vars:
        zabbix_server: 10.10.10.10, 10.0.0.1
        zabbix_server_active: 10.10.10.10

      roles:
         - deploy-zabbix-agent

License
-------

BSD

Author Information
------------------

https://github.com/Branrir