# eql-snmp_exporter

YAML config for snmp_exporter to monitor Dell Equallogic with snmp service enbaled and storing data in prometheus, visualization by grafana.

It contains also original generator.yml for generating final snmp.yml.
```
snmp_exporter --web.listen-address=:9116 --config.file=snmp.yml
```

![grafana example](https://github.com/przemas75/eql-snmp_exporter/raw/master/grafana.png "grafana example")