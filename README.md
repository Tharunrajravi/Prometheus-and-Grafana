prometheus-grafana-monitoring

summary:
  - Launched an EC2 instance and configured security group ports for monitoring (3000, 9090, 9100).
  - Installed Prometheus on the EC2 instance to collect system metrics.
  - Installed Node Exporter to expose host metrics like CPU, memory, disk, and network.
  - Configured Prometheus to scrape metrics from Node Exporter.
  - Installed Grafana and added Prometheus as the data source.
  - Imported the Node Exporter dashboard (ID: 1860) to visualize system metrics
    
Metrics Displayed

CPU Usage (%) – shows processor utilization over time.

Memory Usage (%) – displays current RAM consumption.

Disk Usage (%) – indicates storage usage of the system.

Server Uptime – shows how long the server has been running.
