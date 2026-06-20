# Khyzsh Observability Architecture

## Current Features (Implemented in ICT Library Office)

### Logging

- Colored terminal logs
- Category-based logging
- Centralized logger
- File logging
- Log rotation

Categories:

- SERVER
- SCAN
- ATTENDANCE
- NETWORK
- STREAMING
- AUTH
- SOCKET
- UPLOAD
- GRAPHQL
- ERROR

### Metrics

Prometheus counters:

- scanEventsTotal
- attendanceEventsTotal
- authEventsTotal
- networkEventsTotal
- streamingEventsTotal
- socketEventsTotal
- uploadEventsTotal
- graphqlEventsTotal
- errorEventsTotal

### Monitoring Stack

- Prometheus
- Grafana
- Loki
- Promtail

### Security

- Security Logger
- Audit Logger

### Future Targets

- Discord Alerts
- Telegram Alerts
- Email Alerts
- OpenTelemetry
- Distributed Tracing
- AI Anomaly Detection