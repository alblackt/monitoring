# Monitoring templates
Common monitoring templates. 

 ## Prometheus with Grafana
 Configuration template for setting up Prometheus, Node Exporter, Grafana, and cAdvisor using Docker Compose.
 
 ### To make directories and YAML-files first run: 
 
``` 
mkdir -p promgrafnode/prometheus && mkdir -p promgrafnode/grafana/provisioning && wget https://raw.githubusercontent.com/alblackt/monitoring/main/docker-compose.yml -O ./promgrafnode/docker-compose.yml && wget https://raw.githubusercontent.com/alblackt/monitoring/main/prometheus.yml -O ./promgrafnode/prometheus/prometheus.yml
```
Check your UID (id -u) and paths in docker-compose.yml
Check IP address in prometheus.yml

Run 
```
docker compose up -d
```
You will be able to log in to Grafana http://IP_ADDRESS:3000 (admin/admin)


 ### Prometheus Windows exporther can be founbd there:
https://github.com/prometheus-community/windows_exporter

 
 ## Uptime-Kuma
 Configuration template for setting up Uptime-Kuma using Docker Compose.
