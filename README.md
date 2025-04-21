# Ansible_and_roles
[Roles description](roles/README.md)

## Playbooks

### by_setup:
roles:
- ubuntu_setup
- docker_install
- docker-compose_install
- node_exporter_install
- timezone_set

Open ports in UFW

### grafana:
roles:
- ubuntu_setup
- grafana_install 

Open ports in UFW

### jenkins_update_PB:
roles:
- jenkins_update

### minebook:
Download, install and run minecraft server

### ping:
Test access to server

### prometheus:
roles:
- prometheus_install

Open ports in UFW