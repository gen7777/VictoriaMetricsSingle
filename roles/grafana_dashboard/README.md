## Grafana_dashboard
---
Для добавления новых дашбодов, нужно поместить `json` файл в папку `files`:

```
roles/grafana_dashboard/files/node-exporter.json
roles/grafana_dashboard/files/openvpn-node-exporter.json
roles/grafana_dashboard/files/nginx-exporter.json
roles/grafana_dashboard/files/mydashboard.json
```

В папке `defaults` добавить переменную с именем файла дашборда:
```
grafana_exporters:
  - node-exporter
  - openvpn-node-exporter
  - nginx-exporter
  - mydashboard
```
