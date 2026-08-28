# Monitoring and Alerting Standard

## Coverage model

Every production service should expose signals for availability, latency, errors, capacity, dependency health, security-relevant change, and backup or recovery state.

| Signal | Healthy | Warning | Critical | Evaluation window | Owner | Runbook |
|---|---|---|---|---|---|---|
| | | | | | | |

## Alert quality

An alert must identify the affected service, observable symptom, severity, first diagnostic action, runbook, ownership path, and suppression or maintenance behavior.

## Review checks

- [ ] Alerts indicate user or operational impact
- [ ] Thresholds use evidence rather than defaults
- [ ] Duplicate and unactionable alerts are removed
- [ ] Team-owned destinations replace individual recipients
- [ ] Escalation and after-hours expectations are explicit
- [ ] Dashboards distinguish stale data from healthy state
- [ ] Synthetic checks validate critical user journeys
- [ ] Alert effectiveness is reviewed after incidents
