# Moodle Directory Structure


A Moodle installation typically has a web-accessible application directory containing Moodle PHP files. This is sometimes located under a web server directory such as `/var/www/html/moodle`, but the exact path depends on the server setup.

Common Moodle application folders include:

| Directory/File | Simple Purpose |
|---|---|
| `admin/` | Administration scripts and site administration features |
| `auth/` | Authentication plugins |
| `blocks/` | Block plugins shown in course or dashboard pages |
| `course/` | Course display and management code |
| `mod/` | Activity modules such as quiz, forum, and assignment |
| `theme/` | Moodle themes |
| `user/` | User profile and account-related code |
| `config.php` | Main configuration file with database and path settings |
| `version.php` | Moodle version information |

Important: The Moodle code directory is not the same as the `moodledata` directory.

The application code directory contains Moodle program files. The `moodledata` directory contains generated and uploaded data.
