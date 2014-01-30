egi-broker
==========

Ansible playbooks for deployment of EGI Broker instances

Before running any playbooks make sure you will use a base CentOS6 (or SL6 or RHEL6) installation. Also check that:

* network configurations on the node is done beforehand (firewall should be setup to deny all inbound connections except on port 22 - ssh and ntp client ports)
* ntp client is configured properly
* The packages redhat-lsb, yum-utils are installed

Optional packages (depending on your needs) may also be installed beforehand (i.e. vim-enchanced, screen, ruby etc). 

