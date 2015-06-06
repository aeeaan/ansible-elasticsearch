correcthorse.elasticsearch
=========

A role for installing elasticsearch. The focus is on using elasticsearch as part of a logstash/kibana setup.

Role Variables
--------------

| Variable				| Default			| Notes				|
| :--- 					| :---				| :---				|
| elasticsearch_version			| 1.4				| 				|
| elasticsearch_network_host		| 'localhost'			|				|

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: correcthorse.elasticsearch }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
