# `moodledata`


The `moodledata` directory is a critical storage area used by Moodle. It should not normally be directly accessible from the public web.

The `moodledata` directory may contain:

- Uploaded course files.
- Assignment submissions.
- Cache files.
- Session files, depending on configuration.
- Temporary files.
- Generated files.
- Language packs.
- File repository content.

Important concepts:

- Moodle stores file metadata in the database.
- Moodle stores the actual file content in the file storage system under `moodledata`.
- Files are not normally stored using the original uploaded filename in a simple folder structure.
- Deleting files manually from `moodledata` can break Moodle content.

Security note: `moodledata` should be outside the public web root or protected so users cannot browse it directly through a URL.
