juniper-switches
=========

1. Juniper Switch - Chassis Stats
=====

Requirements
-----

All this templates were tested with Zabbix 2.0.x and Centos 6.x x86_64.

Supproted devices are:
```
Switches EX series (tested on 4200,2200)
Juniper Qfabric
Juniper VC (virtual chassis) with EX 3300
```

Instalation
-----

1. download "advsnmp.discovery" to your zabbix-server 
(from czhujer/Zabbix-Addons REPO)

```
[root@..]# cd /etc/zabbix/externalscripts
[root@..]# wget https://raw.github.com/czhujer/Zabbix-Addons/master/advsnmp.discovery/advsnmp.discovery
[root@..]# chmod 755 advsnmp.discovery
[root@..]# chown root:root advsnmp.discovery
```

2. import xml file to zabbix server

3. enjoy it!

[OPTIONAL] check yours result of discovery with examples in docs-verification folder

Monitored items
------

* Cpu usage

* Memory (buffer) usage

* Temperature


Changes
-------

v1.1 - 2014/10/07 - division of discovery rule
v1.0 - 2013/08/14 - initial version


License
-------

This template were distributed under GNU General Public License 2.

### Copyright

Copyright (c) 2013 - 2014 Patrik Majer
  
### Authors

Patrik Majer
      (patrik.majer.pisek |at| gmail |dot| com)