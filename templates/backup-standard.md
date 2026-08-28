# Backup and Restore Standard

## Required outcomes

Backups must be encrypted, monitored, retained according to business need, protected from the failure domain they cover, and proven through restoration.

## Service profile

| Component | Criticality | RPO | RTO | Backup method | Frequency | Retention | Repository |
|---|---|---|---|---|---|---|---|
| | | | | | | | |

## Controls

- [ ] Backup identity uses least privilege
- [ ] Repository access is restricted and audited
- [ ] At least one copy is isolated or immutable
- [ ] Encryption keys have documented recovery
- [ ] Job failure reaches an owned alert destination
- [ ] Capacity and retention are monitored
- [ ] Restore procedures avoid overwriting the only good copy
- [ ] Restore tests validate application behavior and data integrity

## Restore evidence

Record date, operator, source recovery point, destination, duration, validation performed, defects found, and corrective actions.
