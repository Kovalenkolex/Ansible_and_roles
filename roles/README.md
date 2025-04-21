# Ansible_and_roles
---
### adGuard_install:
- check docker, docker-compose
- run adGuardHome in docker
- open ports

### docker_install:
- install docker

### docker-compose_install:
- check docker installation 
- install docker-compose

### grafana_install:
- install Grafana
- configure Prometheus as Grafana datasource

### jenkins_update:
- download jenkins.war
- replace an old version with the new one
- reload jenkins

### mine_server:
- install openJDK
- download and run installer
- run the server
- accept EULA
- download mods
- run the server

### node_exporter_install:
- download and extract node exporter from archive
- create Node Exporter systemd service file
- allow port 9100 via UFW

### prometheus_install:
- download and extract Prometheus from archive
- create Prometheus configuration file
- create Prometheus systemd service file
- reload systemd

### python_upgrade:
- check python version
- del python if not target version
- install target version

### timezone_set:
- apt install tzdata
- timezone set
- cron reload

### ubuntu_setup:
- apt update
- apt upgrade
- clean up
- install UFW
- allow SSH through UFW
- disable password authentication in SSH config
- enable public key authentication in SSH config