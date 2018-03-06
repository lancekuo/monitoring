FROM grafana/grafana:5.0.0
COPY ds_prometheus.yaml /etc/grafana/provisioning/datasources/prometheus.yaml
COPY db_general.yaml    /etc/grafana/provisioning/dashboards/general.yaml
COPY 893-v24.json           /etc/grafana/provisioning/dashboards/default/893.json
COPY 609.json           /etc/grafana/provisioning/dashboards/default/609.json

