# Backend Workflow


When a user opens a Moodle page, several things happen behind the scenes.

Example: Student opens a course page.

1. The browser sends a request to the Moodle web server.
2. Moodle checks whether the user is logged in.
3. Moodle loads user session information.
4. Moodle checks the user’s enrolment and permissions.
5. Moodle queries the database for course sections, activities, settings, and access rules.
6. Moodle may retrieve files from `moodledata` if needed.
7. Moodle applies the selected theme.
8. The final page is sent back to the browser.

Example: Teacher uploads an assignment file.

1. Teacher selects and uploads a file.
2. Moodle checks upload size limits and permissions.
3. Moodle stores file metadata in the database.
4. Moodle stores file content in `moodledata`.
5. Moodle updates the activity or course record.
6. Students with access can later download the file through Moodle-controlled access.
