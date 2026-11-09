# School Management System

A legacy PHP/MySQL school-administration prototype covering students, teachers, classes, sections, subjects and attendance.

## Repository map

- Root PHP pages: dashboard and administrative screens.
- `class/School.php`: database-backed operations.
- `class/config.php`: legacy connection configuration.
- `js/`: screen interactions and table controls.
- `db_dump/`: original SQL scripts; review all schema and seed content before use.

## Development status

This is historical project code. It is not currently verified for production. It needs a dedicated review of modern PHP compatibility, database configuration, authentication, password handling, query safety and personal-data handling before deployment.

To investigate locally, use a disposable PHP/MySQL environment with synthetic records. Inspect `class/School.php` as well as `class/config.php`: the connection currently contains its own hardcoded local development configuration. No working production installation is claimed.

This documentation update preserves the existing implementation. Setup, database import and full application tests have not been rerun as part of the GitHub presentation cleanup.
