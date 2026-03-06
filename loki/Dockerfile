FROM grafana/loki:2.9.0
# النسخة 2.9.0 مستقرة جداً ولا تطلب التعقيدات الجديدة
COPY loki-config.yml /etc/loki/local-config.yaml
CMD ["-config.file=/etc/loki/local-config.yaml"]
