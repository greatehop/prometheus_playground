prometheus+grafana+alert-manager+node-exporter

docker volume create --name=prom_data
docker-compose up -d

grafana node-exporter dashboard
https://grafana.com/grafana/dashboards/1860-node-exporter-full/
