# deploy_zabbix_agent

* Playbook `install_zabbix_agents.yml` for open firewall and install new zabbix agents.
* Playbook `playbook_del.yml` for purge old zabbix agents.

## Main variables

There are some variables in de default/main.yml which can (Or needs to) be overridden:

* `zabbix_agent_server`: The ip address for the zabbix-server or zabbix-proxy.

* `zabbix_agent_serveractive`: The ipaddress for the zabbix-server or zabbix-proxy for active checks.

* `zabbix_version`: This is the version of zabbix. Default it is 4.0, but can be overridden to one of the versions mentioned in [Zabbix Versions](#zabbix-versions).
