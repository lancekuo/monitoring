FROM grafana/grafana:5.2.4
COPY ds_prometheus.yaml /etc/grafana/provisioning/datasources/prometheus.yaml
COPY db_general.yaml    /etc/grafana/provisioning/dashboards/general.yaml
COPY --chown=grafana:grafana 609.json           /etc/grafana/provisioning/dashboards/default/609.json
COPY --chown=grafana:grafana 405.json           /etc/grafana/provisioning/dashboards/default/405.json
#COPY 2428_rev6.json     /etc/grafana/provisioning/dashboards/default/2428_rev6.json

