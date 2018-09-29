ELK configuration for LogNet
====

## Run:

```cmd
ES_PATH_CONF=E:\LogNet\github_repos\elk-config\elasticsearch
E:\LogNet\elasticsearch-6.4.1\bin\elasticsearch.bat

E:\LogNet\kibana-6.4.1-windows-x86_64\bin\kibana.bat -c E:\LogNet\github_repos\elk-config\kibana.yml

E:\LogNet\logstash-6.4.1\bin\logstash.bat -f E:\LogNet\github_repos\elk-config\logstash.conf

E:\LogNet\filebeat-6.4.1-windows-x86_64\filebeat.exe -e -c E:\LogNet\github_repos\elk-config\filebeat.yml
```

## Browse:

http://localhost:5601
