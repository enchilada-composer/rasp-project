# Rasp-Project

This project sets up a Raspberry Pi cluster using Ansible. It automates the installation and configuration of:

- **Consul** for service discovery and cluster coordination
- **Prometheus + Grafana** for monitoring and visualization
- **Prometheus node_exporter** on each Raspberry Pi for collecting metrics

## Goals

- Automate setup of all nodes using Ansible
- Run Consul in cluster mode on all Raspberry Pis
- Install Prometheus and Grafana on one node
- Run node_exporter on every node and collect metrics centrally
- Visualize metrics using custom dashboards in Grafana
- Keep all setup scripts version-controlled in this GitHub repository
