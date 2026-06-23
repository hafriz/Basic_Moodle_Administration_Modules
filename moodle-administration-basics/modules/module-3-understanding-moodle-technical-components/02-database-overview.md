# Database Overview


The Moodle database stores structured information used by the platform.

Examples of database content:

- User accounts and profile information.
- Course records.
- Course categories.
- Activity settings.
- Enrolment records.
- Role assignments.
- Grades and gradebook data.
- Logs and event records.
- Site configuration settings.
- Completion tracking records.

Common database systems used with Moodle include MariaDB, MySQL, and PostgreSQL.

For beginner administrators, it is not necessary to memorize Moodle table names. However, it is important to understand that most settings and learning records are stored in the database.

Administrative implications:

- A complete backup must include the database.
- Database performance affects Moodle performance.
- Database connectivity problems can make the entire site unavailable.
- Direct database changes should be avoided unless performed by experienced administrators with proper backups.
