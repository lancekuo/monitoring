FROM grafana/grafana:5.0.0-beta4
COPY ds_prometheus.yaml /etc/grafana/provisioning/datasources/prometheus.yaml
COPY db_general.yaml    /etc/grafana/provisioning/dashboards/general.yaml
COPY JSON-TestNet.json  /etc/grafana/provisioning/dashboards/default/TestNet.json

