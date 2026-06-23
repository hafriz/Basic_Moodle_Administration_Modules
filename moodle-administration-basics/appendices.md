# Appendices

## Appendix A: One-Day Trainer Checklist

Before training:

- Prepare Moodle demo site.
- Create administrator, teacher, and student demo accounts.
- Create sample course category.
- Create sample course.
- Prepare sample PDF or document upload.
- Prepare sample user CSV if demonstrating upload.
- Confirm projector and internet access.
- Confirm demo site is not production.
- Prepare architecture diagram.
- Prepare troubleshooting scenarios.

During training:

- Keep examples simple.
- Ask participants to connect concepts to their organization.
- Avoid deep code-level explanations.
- Use short recap points after each module.
- Keep hands-on activities controlled and safe.

After training:

- Share documentation and links.
- Provide recommended next steps.
- Collect feedback.
- Record unanswered questions for follow-up.

## Appendix B: Moodle Technical Terms Glossary

| Term | Simple Definition |
|---|---|
| LMS | Learning Management System, a platform for managing online learning |
| Course | A learning space containing resources, activities, participants, and grades |
| Category | A container used to organize courses |
| Resource | Content item such as a file, page, folder, or URL |
| Activity | Interactive learning item such as assignment, quiz, forum, or feedback |
| Authentication | Process of verifying user identity during login |
| Enrolment | Process of giving a user access to a course |
| Role | A named set of permissions, such as teacher or student |
| Permission/Capability | A specific action a user is allowed or not allowed to perform |
| Context | The area where a role applies, such as site, category, course, or activity |
| Theme | Package controlling the visual appearance of Moodle |
| Plugin | Add-on that extends Moodle functionality |
| Cron | Scheduled background process that runs Moodle tasks |
| `moodledata` | File storage directory used by Moodle for uploaded and generated files |
| Cache | Stored temporary data used to improve speed |
| Scheduled task | Moodle background task run by cron |
| Cohort | Site-wide or category-wide group of users for bulk enrolment or management |
| Backup | Copy of site or course data for recovery purposes |
| Restore | Process of recovering data from a backup |

## Appendix C: Sample Moodle Access Troubleshooting Checklist

Use this checklist when a user cannot access a course or activity.

1. Can the user log in?
2. Is the user account active or suspended?
3. Is the course visible?
4. Is the user enrolled in the course?
5. Does the user have the correct role?
6. Is the activity visible?
7. Are there date restrictions?
8. Are there group restrictions?
9. Are there completion restrictions?
10. Is the issue limited to one browser or device?
11. Are other users affected?
12. Were there recent changes to course settings?
13. What do Moodle logs show?
14. Has the issue been documented?

## Appendix D: Sample Change Log Template

| Date | Change | Environment | Changed By | Reason | Tested By | Rollback Plan |
|---|---|---|---|---|---|---|
| _YYYY-MM-DD_ | _Describe change_ | _Staging/Production_ | _Name_ | _Reason_ | _Name_ | _Rollback steps_ |

## Appendix E: Sample Incident Record Template

| Field | Details |
|---|---|
| Incident title | _Short description_ |
| Date and time reported | _Insert date/time_ |
| Reported by | _Name or department_ |
| Affected users | _One user, one course, many users, whole site_ |
| Symptoms | _Describe what users experience_ |
| Initial checks | _Logs, cron, database, server, course settings_ |
| Root cause | _Confirmed cause_ |
| Fix applied | _Action taken_ |
| Validation | _How fix was confirmed_ |
| Prevention | _Future prevention steps_ |
| Follow-up owner | _Name/team_ |

## Appendix F: Suggested Slide Outline

| Slide Range | Topic |
|---|---|
| 1–3 | Welcome, objectives, agenda |
| 4–8 | What Moodle is and LMS concepts |
| 9–14 | Moodle administration basics |
| 15–20 | Users, roles, permissions, courses |
| 21–27 | Technical components and architecture |
| 28–33 | Performance overview |
| 34–39 | Customization, themes, plugins, integrations |
| 40–45 | Maintenance and troubleshooting |
| 46–48 | Scenarios and discussion |
| 49–50 | Recap, resources, Q&A |
