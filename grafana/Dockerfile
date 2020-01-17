FROM grafana/grafana:latest
MAINTAINER lcb "xinglou123@163.com"

ENV TZ "Asia/Shanghai"

COPY grafana/provisioning /etc/grafana/provisioning
COPY grafana/config.ini /etc/grafana/config.ini
COPY grafana/dashboards /var/lib/grafana/dashboards
