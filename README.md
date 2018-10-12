ELK configuration for LogNet
====

## Run:

Production:

```cmd
ES_PATH_CONF=E:\LogNet\github_repos\elk-config\elasticsearch
E:\LogNet\elasticsearch-6.4.1\bin\elasticsearch.bat

E:\LogNet\kibana-6.4.1-windows-x86_64\bin\kibana.bat -c E:\LogNet\github_repos\elk-config\kibana.yml

E:\LogNet\logstash-6.4.1\bin\logstash.bat -f E:\LogNet\github_repos\elk-config\logstash.conf

E:\LogNet\filebeat-6.4.1-windows-x86_64\filebeat.exe -e -c E:\LogNet\github_repos\elk-config\filebeat.yml
```

Home:

```cmd
ES_PATH_CONF=J:\github_repos\elk-config\elasticsearch
J:\LogNet\elasticsearch-6.4.1\bin\elasticsearch.bat

J:\LogNet\kibana-6.4.1-windows-x86_64\bin\kibana.bat -c J:\github_repos\elk-config\kibana.yml

J:\LogNet\logstash-6.4.1\bin\logstash.bat -f J:\github_repos\elk-config\logstash.conf

J:\LogNet\filebeat-6.4.1-windows-x86_64\filebeat.exe -e -c J:\github_repos\elk-config\filebeat.yml
```

Work:

```cmd
ES_PATH_CONF=I:\github_repos\elk-config\elasticsearch
I:\LogNet\elasticsearch-6.4.1\bin\elasticsearch.bat

I:\LogNet\kibana-6.4.1-windows-x86_64\bin\kibana.bat -c I:\github_repos\elk-config\kibana.yml

I:\LogNet\logstash-6.4.1\bin\logstash.bat -f I:\github_repos\elk-config\logstash.conf

I:\LogNet\filebeat-6.4.1-windows-x86_64\filebeat.exe -e -c I:\github_repos\elk-config\filebeat.yml
```

## Browse:

http://localhost:5601
