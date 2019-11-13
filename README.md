# Vigilant Sentry
Network Security Monitoring and Alerting Tools

Vigilant Sentry is planned to be a collection of scripts, templates and configurattion tools.

The vision is as follows:  Making use of the Enterprise grade monitoring framework Zabbix, a machine is deployed to a local area network.  That machine can either be a standalone Zabbix server or a Zabbix proxy to relay to another Zabbix server.  There will be a list of required tools that will be installed for the purposes of security assessments of the local network.  (Port scans, vulnerability scans, potentially honepots as well.)  All of these tools will be integrated into the Zabbix reporting and alerting so that IT will have a good awareness of unusual activity on the network.

Our goal is to make it as easy to simply drop in place as possible with minimal configuraton.  There will be a need for some configuration for other features.

We hope to include monitoring of domain name expiry, SSL monitoring, blacklist monitoring as well as a host of other features to give IT as good a "one place to look" dashboard for all issues on the network.
