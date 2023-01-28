# Monitoring templates
Common monitoring templates. 

 ## Prometheus with Grafana
 Configuration template for setting up Prometheus, Node Exporter, Grafana, and cAdvisor using Docker Compose.
 
``` 
mkdir -p promgrafnode/prometheus && mkdir -p promgrafnode/grafana/provisioning && wget https://raw.githubusercontent.com/alblackt/monitoring/main/docker-compose.yml -O ./promgrafnode/docker-compose.yml && wget https://raw.githubusercontent.com/alblackt/monitoring/main/prometheus.yml -O ./promgrafnode/prometheus/prometheus.yml
```
 
 
 ## Uptime-Kuma
 Configuration template for setting up Uptime-Kuma using Docker Compose.
