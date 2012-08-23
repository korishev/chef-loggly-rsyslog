Description
===========
Configures logging to loggly.com via rsyslog by dropping a file into /etc/rsyslog.d/

Requirements
============
loggly.com account
Syslogging with rsyslog installed and setup to handle tcp logging
Tested only on Ubuntu 12.04

Attributes
==========
* `node['loggly-rsyslog']['logging_host']`  - Defaults to logs.loggly.com
* `node['loggly-rsyslog']['tcp_port']`      - The port you were assigned by loggly for this input

Usage
=====
Set logging port and (optionally) host in a role, and add the default loggly-rsyslog recipe to your run list.

