FROM prom/node-exporter:v0.15.2

ENV NODE_EXPORTER_BIN=/bin/node_exporter

COPY ./rootfs /

ENTRYPOINT  [ "./docker-entrypoint.sh" ]
CMD [ "/bin/node_exporter" ]
