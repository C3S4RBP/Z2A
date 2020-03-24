# Zabbix to Aranda Service Desk V8

java jar which allows the creation or closure of a ticket in Aranda Service desk v8, the trigger is the events generated from zabbix.

It has a configuration file where variables such as the zabbix engine are defined, either postgres or mysql, in addition to the case categorization.

# Installation

```Linux
$ cd /etc/z2a/
$ wget -r https://github.com/C3S4RBP/Z2A/tree/master/source
$ java -jar z2a.jar "0" "0" "1992.10.13" "00:00:00" "0" "Creacion de archivos" "0"
$ chmod 664 /var/log/z2a/z2a.log
$ sudo chown zabbix:zabbix /var/log/z2a/z2a.log
```

# Configuration
View manual

# Autor
Cesar Bejarano
