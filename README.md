Ansible Role: elk
=========

Installs Elastic Stack via docker

Manages the required certificate authority to use mutual tls between beats and logstash

Requirements
------------

* Installed docker and docker-compose
* Installed docker python module


Role Variables
--------------

```yaml
elk_ca_file: # mandatory during all tasks
elk_logstash_cert_file: # mandatory during main tasks
elk_logstash_cert_key_file: # mandatory during main tasks
elk_beat_cert_file: # mandatory during beat tasks
elk_beat_cert_key_file: # mandatory during beat tasks
```
