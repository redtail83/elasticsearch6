Ansible Role: ElasticSearch 6
=========

Install ElasticSearch 6 for CentOS linux.

Requirements
------------

None.

Role Variables
--------------

Here is the list of all variables for this role.
```yml
# Environment Variable JAVA_HOME
java_home: /opt/java/current
```

Dependencies
------------

This role depends on:

* redtail83.adoptopenjdk8_hotspot

Example Playbook
----------------

CentOS 7:

    - hosts: servers
      roles:
         - { role: redtail83.elasticsearch6 }

License
-------

MIT
