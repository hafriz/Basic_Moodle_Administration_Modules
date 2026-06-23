# Best Practices

## Administration Best Practices

- Use named administrator accounts rather than shared accounts.
- Limit site administrator access to a small trusted group.
- Apply the principle of least privilege.
- Use role assignments at the most appropriate context.
- Document major configuration changes.
- Test changes in staging before production.
- Avoid changing many settings at once.
- Use maintenance windows for high-impact changes.
- Communicate planned changes to users.
- Keep a rollback plan for upgrades and plugin changes.

## User Management Best Practices

- Use institutional authentication where appropriate.
- Avoid duplicate accounts.
- Suspend accounts when access should be temporarily disabled.
- Delete accounts only according to policy and data retention rules.
- Review privileged accounts regularly.
- Use cohorts for group-based enrolment where suitable.
- Keep user profile fields consistent.
- Protect personal data and follow privacy requirements.

## Course Management Best Practices

- Use a clear course category structure.
- Agree on naming conventions for course full names and short names.
- Hide courses until they are ready for students.
- Use course templates where possible.
- Encourage teachers to organize long courses into sections.
- Archive old courses according to institutional policy.
- Review course backup and retention requirements.
- Avoid placing too much content on a single course page.

## Roles and Permissions Best Practices

- Do not assign site administrator access for routine course management.
- Assign roles in the correct context.
- Review custom roles carefully.
- Document any role changes.
- Test role behavior using a sample user.
- Avoid granting broad permissions to solve a narrow problem.
- Review manager and course creator permissions periodically.

## Plugin Best Practices

- Install only necessary plugins.
- Check compatibility with the Moodle version.
- Review plugin maintenance status.
- Test plugins in staging.
- Confirm privacy and data handling implications.
- Keep plugins updated.
- Remove unused plugins after proper review.
- Document plugin purpose, owner, and support contact.

## Theme and Branding Best Practices

- Use supported themes.
- Test visual changes on multiple devices.
- Maintain accessibility, especially color contrast and keyboard navigation.
- Avoid excessive undocumented custom CSS.
- Keep branding simple and consistent.
- Test themes before Moodle upgrades.
- Keep a backup of theme settings or documentation.

## Backup and Recovery Best Practices

- Back up the Moodle database.
- Back up `moodledata`.
- Back up Moodle application code and custom plugins/themes.
- Test restore procedures regularly.
- Store backups securely.
- Monitor backup success and failure.
- Keep backups according to retention policy.
- Ensure backups are not stored only on the same server.
- Document recovery steps and responsibilities.

## Performance Best Practices

- Monitor server resources and trends.
- Run cron regularly.
- Schedule heavy tasks outside peak hours.
- Use caching appropriately.
- Keep Moodle and plugins updated.
- Review slow reports and large courses.
- Encourage streaming platforms for large video content.
- Plan for peak academic events.
- Maintain a staging environment for testing.

## Security Best Practices

- Keep Moodle, plugins, server packages, and dependencies updated.
- Use HTTPS.
- Use strong authentication practices.
- Limit administrator access.
- Review logs for suspicious activity.
- Protect `moodledata` from direct web access.
- Secure database credentials.
- Follow data privacy requirements.
- Review file upload policies.
- Disable unused authentication methods.

## Troubleshooting Best Practices

- Define the problem clearly before changing settings.
- Determine the scope of the issue.
- Check recent changes.
- Review logs and monitoring data.
- Reproduce the issue when possible.
- Make one change at a time.
- Document the fix.
- Escalate early when the problem belongs to another technical area.
- Communicate clearly with affected users.

---
