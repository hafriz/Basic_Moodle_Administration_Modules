# Troubleshooting Scenarios

The following realistic cases can be used for discussion, role play, or guided troubleshooting practice.

## Scenario 1: Students Cannot Access a Course

**Case:** Several students report that they can log in to Moodle, but they cannot find the course “Introduction to Economics.”

**Possible causes:**

- Students are not enrolled.
- Course is hidden.
- Course start date or visibility settings are incorrect.
- Course is in the wrong category.
- Dashboard filters hide the course.
- Cohort synchronization has failed.
- Enrolment method is disabled.

**Suggested troubleshooting steps:**

1. Confirm affected students can log in.
2. Search for the course as an administrator.
3. Check course visibility.
4. Check enrolment methods.
5. Check whether affected users are enrolled.
6. Check role assignment.
7. Check cohort sync if used.
8. Confirm whether the course appears on the dashboard or through direct course search.

**Resolution example:** The course was created but left hidden. The administrator changes course visibility to show, confirms enrolments, and notifies the lecturer.

## Scenario 2: Forum Notifications Are Not Being Sent

**Case:** Teachers report that students are not receiving forum notification emails.

**Possible causes:**

- Cron is not running.
- Scheduled tasks are failing.
- SMTP server is misconfigured.
- Email is blocked by spam filtering.
- Users disabled email notifications in preferences.
- Forum subscription settings are not configured as expected.

**Suggested troubleshooting steps:**

1. Check whether cron has run recently.
2. Review scheduled task failures.
3. Check outgoing mail configuration.
4. Send a test email if available.
5. Review mail server logs if accessible.
6. Check forum subscription settings.
7. Test with one user account.

**Resolution example:** Cron had stopped after a server migration. The system administrator restores the cron schedule, runs cron manually, and monitors email delivery.

## Scenario 3: File Uploads Fail for Teachers

**Case:** Teachers cannot upload large PDF files or lecture recordings.

**Possible causes:**

- Moodle course upload limit is too low.
- Site upload limit is too low.
- PHP upload limit is too low.
- Web server request size limit is too low.
- Disk space is full.
- File type restrictions apply.
- `moodledata` permissions are incorrect.

**Suggested troubleshooting steps:**

1. Confirm file size and file type.
2. Check Moodle site upload limit.
3. Check course upload limit.
4. Check PHP and web server upload limits.
5. Check available disk space.
6. Check `moodledata` permissions.
7. Recommend streaming service for very large video files.

**Resolution example:** The course upload limit was set lower than the site limit. The administrator adjusts the course setting and advises the teacher to use the institutional video platform for large recordings.

## Scenario 4: Moodle Is Slow During Online Quiz

**Case:** Moodle becomes slow during a scheduled online quiz for a large class.

**Possible causes:**

- Too many concurrent quiz attempts.
- Insufficient PHP workers or web server capacity.
- Database load is too high.
- Quiz contains complex question types.
- Autosave frequency and attempt behavior increase load.
- Other scheduled tasks or backups are running at the same time.
- Network bandwidth is limited.

**Suggested troubleshooting steps:**

1. Identify number of active users and quiz attempts.
2. Check server CPU, memory, and process limits.
3. Check database load.
4. Check web server and PHP error logs.
5. Check whether backups or heavy scheduled tasks are running.
6. Review quiz settings and question types after the incident.
7. Plan capacity testing before future high-stakes exams.

**Resolution example:** Automated backups were running during the quiz window. The schedule is moved outside exam hours, and the institution plans load testing before the next exam period.

## Scenario 5: Theme Looks Broken After Update

**Case:** After a Moodle upgrade, the site layout appears broken and some buttons are misaligned.

**Possible causes:**

- Theme is incompatible with the new Moodle version.
- Custom CSS conflicts with updated HTML structure.
- Caches need to be purged.
- A plugin block or activity affects layout.
- Browser cache contains old assets.

**Suggested troubleshooting steps:**

1. Purge Moodle caches in a controlled way.
2. Test in another browser or private window.
3. Switch temporarily to a standard theme in staging.
4. Check theme version compatibility.
5. Review custom CSS.
6. Check browser developer console for asset errors.
7. Contact theme vendor or developer if needed.

**Resolution example:** The custom theme was not compatible with the upgraded Moodle version. The team applies an updated theme release in staging, tests it, then deploys to production.

---
