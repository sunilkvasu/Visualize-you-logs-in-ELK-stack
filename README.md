# Visualize-you-logs-in-ELK-stack

Configure logstash

Restart logstash

systemctl restart logstash

Configure rsyslog.conf on the remote host

*.* @<ELK_SERVER_IP>

Restart rsyslog on the remote host

systemctl restart rsyslog
