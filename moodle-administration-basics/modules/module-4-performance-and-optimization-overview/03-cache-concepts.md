# Cache Concepts


A cache stores frequently used data so Moodle does not need to rebuild or reload it every time.

Simple analogy: A cache is like keeping frequently used documents on your desk instead of walking to the archive room every time.

Moodle uses caching for many internal operations. Effective caching can reduce database load and speed up page generation.

Common cache-related concepts:

- **Application cache**: Stores commonly used application data.
- **Session storage**: Stores logged-in user session information.
- **Theme cache**: Stores generated theme assets.
- **Language string cache**: Helps Moodle load interface text faster.
- **Cache purge**: Clears cached content so Moodle rebuilds it.

Administrators may use “Purge all caches” after certain configuration changes, plugin updates, or theme changes. However, purging caches on a busy production site may temporarily increase load because Moodle must rebuild cached data.
