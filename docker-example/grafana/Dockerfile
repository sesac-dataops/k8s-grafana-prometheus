#This is only used for export image

FROM grafana/grafana:latest

ARG USER
ARG PASSWORD
ARG PORT=3000

ENV GF_SECURITY_ADMIN_USER=${USER}
ENV GF_SECURITY_ADMIN_PASSWORD=${PASSWORD}

COPY datasource.yml /etc/grafana/provisioning/datasources/datasource.yml

EXPOSE ${PORT}