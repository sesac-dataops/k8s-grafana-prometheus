#This is only used for export image

FROM prom/prometheus:latest

ARG PORT=9090

COPY prometheus.yml /etc/prometheus/prometheus.yml

EXPOSE ${PORT}

CMD [ "--config.file=/etc/prometheus/prometheus.yml" ]
