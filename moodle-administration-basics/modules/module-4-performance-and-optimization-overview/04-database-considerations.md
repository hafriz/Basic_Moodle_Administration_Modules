# Database Considerations


The database is one of the most important performance components in Moodle. Many Moodle pages require database queries.

Database factors include:

- Database server size and resource allocation.
- Query performance.
- Database indexes.
- Table size, especially logs and activity records.
- Backup and maintenance schedules.
- Network latency between Moodle and the database server.
- Database configuration parameters.

Beginner administrators do not need to tune every database parameter, but they should know when to involve database administrators.

Situations that may require DBA involvement:

- Slow reports across the whole site.
- Database server CPU or memory consistently high.
- Queries timing out.
- Large log tables affecting backup or reporting.
- Database disk space approaching full capacity.
- Need for replication, high availability, or advanced backup strategy.
