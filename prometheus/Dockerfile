FROM prom/prometheus:v2.4.2

COPY prometheus.yml /etc/prometheus/prometheus.yml
COPY docker-entrypoint.sh /etc/prometheus/
# In order to create symbolic link in the image
ADD symbolic.tar /etc/prometheus

ENTRYPOINT ["/etc/prometheus/docker-entrypoint.sh"]
# Gonna move this commands to docker-compose file, but would leave here just for refernece
# CMD ["--config.file=/etc/prometheus/prometheus.yml", "--storage.tsdb.path=/prometheus", "--web.console.libraries=/etc/prometheus/console_libraries", "--web.console.templates=/etc/prometheus/consoles"]
