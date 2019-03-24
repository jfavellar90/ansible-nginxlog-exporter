
jfavellar90.nginxlog_exporter for Ansible
============


## Summary

This Ansible role has the following features for [nginxlog_exporter](https://github.com/martin-helmich/prometheus-nginxlog-exporter) (a Nginx metrics exporter for [Prometheus](http://prometheus.io/)):

 - Install nginxlog_exporter by downloading the configured release from [releases page](https://github.com/martin-helmich/prometheus-nginxlog-exporter/releases).
 - Handlers for restart/reload/stop events.



## Role Variables

### Mandatory variables

None.



### Optional variables


TBD


## Handlers

- `restart nginxlog_exporter`

- `reload nginxlog_exporter`

- `stop nginxlog_exporter`



## Usage


### Step 1: add role

Add role name `jfavellar90.nginxlog_exporter` to your playbook file.


### Step 2: add variables

Set vars in your playbook file, if necessary.

Simple example:

```yaml
---
# file: simple-playbook.yml

- hosts: all
  become: True
  roles:
    - jfavellar90.nginxlog_exporter


```

## Dependencies

None.


## License

MIT License. See the [LICENSE file](LICENSE) for details.
