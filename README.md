# Ansible Google Stackdriver monitoring agent

Ansible role that installs Google Stackdriver monitoring agent

## Variables

+ Downloads the configurations defined by this variable from 
https://github.com/Stackdriver/stackdriver-agent-service-configs/tree/master/etc/collectd.d
```yaml
stackdriver_configs: []
```
+ Copies this files to the configurations folder.
```yaml
stackdriver_custom_config_files: []
```
+ Copies this templates to the configurations folder.
```yaml
stackdriver_custom_config_templates: []
```
