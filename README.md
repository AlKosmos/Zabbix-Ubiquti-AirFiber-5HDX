# Zabbix-Ubiquti-AirFiber-5HDX
Zabbix template for monitoring Ubiquiti AirFiber 5XHD for Zabbix 4.x
Monitors by SNMP and SSH agent, so the template needs ssh user and password for Ubiquiti. 
Uses Dependent items and connects to Ubiquiti onсe for geting data. 

Needs to set up macroses: 
{$SNMP_COMMUNITY}
{$SSH_PASSWORD}
{$SSH_USER}

{$HISTORY} 
{$TRENDS} 
{$UPDATEINT}
