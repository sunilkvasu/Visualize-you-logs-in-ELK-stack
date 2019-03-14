# Visualize-you-logs-in-ELK-stack

Configure logstash, Use: 01-input_syslog.conf

Restart logstash

systemctl restart logstash

Configure rsyslog.conf on the remote host

*.* @<ELK_SERVER_IP>

Restart rsyslog on the remote host

systemctl restart rsyslog

Create index in Kibana

Create search patterens in Kibana

Create visualization in Kibana

Create dashboards in Kibana
