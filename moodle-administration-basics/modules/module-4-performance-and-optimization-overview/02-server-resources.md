# Server Resources


Moodle runs on server infrastructure. The main resource areas are:

| Resource | Why It Matters |
|---|---|
| CPU | Handles PHP processing, page generation, and concurrent requests |
| Memory/RAM | Supports web server processes, PHP workers, caching, and database memory |
| Disk I/O | Affects file uploads, cache reads/writes, database operations, and backups |
| Network | Affects user access, file downloads, integrations, and remote database connections |
| Database capacity | Affects page load time, reports, logs, grades, and activity data |

Common symptoms:

| Symptom | Possible Resource Issue |
|---|---|
| Pages load slowly for everyone | CPU, database, cache, or network issue |
| Uploads fail | Disk space, upload limit, permissions, or web server limit |
| Site is slow during quizzes | High concurrent usage, database load, PHP worker limits |
| Reports take a long time | Database size, indexes, server resources, large log tables |
| Random errors during peak hours | Resource exhaustion or process limits |
