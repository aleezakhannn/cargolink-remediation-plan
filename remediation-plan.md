# CargoLink Remediation Plan

This plan fixes the 12 gaps found in the ISO 27001 gap analysis. All data comes from the sample lab environment.

## Remediation Table

| # | Gap (Control) | Remediation Action | Owner | Priority | Start | Due |
|---|---|---|---|---|---|---|
| 1 | A.8.24 Use of cryptography | Turn on encryption in transit (HTTPS/TLS) and at rest for fleet tracking data | IT Admin | High | 2026-10-19 | 2026-11-06 |
| 2 | A.5.24 Incident management planning | Write a one-page incident response plan with contacts and first steps | IT Admin | High | 2026-10-19 | 2026-10-30 |
| 3 | A.5.30 ICT readiness for continuity | Document a recovery plan for the fleet tracking server and test one restore | IT Admin | High | 2026-11-02 | 2026-11-20 |
| 4 | A.8.8 Technical vulnerabilities | Set a monthly patching schedule for all servers | IT Admin | High | 2026-10-26 | 2026-11-13 |
| 5 | A.8.15 Logging | Turn on activity logging for the cargo manifest database and review it weekly | IT Admin | High | 2026-10-26 | 2026-11-13 |
| 6 | A.5.15 Access control | Write access rules for the manifest database and limit it to named roles | IT Admin | Medium | 2026-11-02 | 2026-11-13 |
| 7 | A.7.10 Storage media | Encrypt the backup drive and keep it in a locked cabinet | IT Admin | Medium | 2026-10-19 | 2026-10-23 |
| 8 | A.8.13 Information backup | Schedule weekly backups and test a restore every month | IT Admin | Medium | 2026-10-26 | 2026-11-06 |
| 9 | A.8.5 Secure authentication | Enable multi-factor authentication on dispatch terminal logins | IT Admin | Medium | 2026-11-09 | 2026-11-27 |
| 10 | A.6.3 Awareness and training | Run a 30-minute security awareness session for dispatch and warehouse staff | Dispatch Manager | Medium | 2026-11-16 | 2026-11-27 |
| 11 | A.8.2 Privileged access rights | Give each admin their own account and remove shared logins | IT Admin | Low | 2026-11-02 | 2026-11-13 |
| 12 | A.8.20 Networks security | Split guest and office Wi-Fi and segment the network on the router | IT Admin | Low | 2026-11-16 | 2026-12-04 |

## Assumptions

- Owners and dates are proposals for this lab exercise, not real commitments.
- IT Admin owns most actions because most gaps are technical. Overlapping work is staggered where possible, and a real rollout may need extra help.
