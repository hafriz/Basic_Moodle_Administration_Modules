# High-Level Architecture


At a high level, Moodle usually includes the following components:

| Component | Simple Explanation |
|---|---|
| Web browser | The interface used by students, teachers, and administrators |
| Web server | Runs Moodle and responds to web requests |
| Moodle application code | PHP application files that provide Moodle functionality |
| Database | Stores users, courses, grades, settings, activity data, and many records |
| `moodledata` | Stores uploaded files, cache data, sessions, temporary files, and generated content |
| Cron | Runs background tasks such as sending emails, processing completion, and cleanup |
| Authentication services | Optional systems used for login, such as LDAP, SSO, or OAuth2 |
| Email service | Sends notifications and password reset messages |

A simplified request flow:

```text
User Browser → Web Server → Moodle Application → Database / moodledata → Response to Browser
```

Some tasks happen in the background:

```text
Cron Scheduler → Moodle Scheduled Tasks → Email, cleanup, reports, completion, notifications
```
