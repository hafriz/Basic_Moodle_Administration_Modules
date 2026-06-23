# Monitoring


Monitoring helps technical staff detect problems before users report them.

Useful monitoring areas:

| Area | What to Monitor |
|---|---|
| Availability | Is Moodle reachable? |
| Web server | Request rate, errors, response time |
| PHP/application | Error logs, process limits, slow requests |
| Database | CPU, memory, connections, slow queries, disk usage |
| Storage | Free space, disk I/O, backup storage |
| Cron | Last run time, failed scheduled tasks |
| Email | Delivery failures, SMTP errors |
| Authentication | Login failures, SSO errors, directory connectivity |
| Security | Administrator changes, suspicious logins, update alerts |

Monitoring should include both technical metrics and user experience. A server may look healthy, but users may still experience slow pages if a specific plugin or external service is failing.
