# Lessons Learned

## Log Rotation

Without rotation, log files can grow indefinitely.

Solution:
- 50 MB per file
- Keep 10 rotated files

## Centralized Logging

Using logger.ts allows adding:

- Metrics
- Alerts
- Loki
- Audit
- Security

without changing business logic.

## Observability

Logging is not observability.

Observability includes:

- Logs
- Metrics
- Monitoring
- Alerting
- Dashboards