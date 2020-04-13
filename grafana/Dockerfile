FROM grafana/grafana:6.7.2

COPY ./root/etc/grafana/grafana.ini /etc/grafana/grafana.ini
COPY ./root/etc/grafana/provisioning/dashboards/graphite-clickhouse.yaml /etc/grafana/provisioning/dashboards/graphite-clickhouse.yaml
COPY ./root/etc/grafana/provisioning/datasources/graphite.yaml /etc/grafana/provisioning/datasources/graphite.yaml
COPY ./root/var/lib/grafana/dashboards/graphite-clickhouse.json /var/lib/grafana/dashboards/graphite-clickhouse.json
