# UniFi Network Telemetry

This stack provides network observability for UniFi networks using:

- UniFi Poller
- InfluxDB 2.x
- Grafana (with provisioning and email alerts)

## Setup

1. Copy `.env.example` to `.env` and edit it with your settings.
2. Run the stack:

```bash
docker compose up -d
```

3. Access:
- Grafana: http://localhost:3000 (admin/changeme)
- InfluxDB: http://localhost:8086

## Email Alerts

Make sure your SMTP settings are valid. Alerts will be sent from Grafana using those credentials.
