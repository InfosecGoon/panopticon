These are the OSSEC-related files for the project.

ossec.conf - this is the configuration file for the WEF collector server. It is the stock configuration, modified to also
monitor Forwarded Events and send them along to the OSSEC server.

local_rules.xml - these are example OSSEC rules to raise alerts from the forwarded Windows logs. The file can be placed in
the /var/ossec/rules directory on the Security Onion server that the WEF collector is reporting to.
