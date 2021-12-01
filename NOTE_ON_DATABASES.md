# Note on Databases

By default, the database created by course are **not** tracked by the repository. This is to prevent merge issues, particularly surrounding user creation. However, with the Academic Parser being almost fully operational, two databases have been manually added to the repository for convenience purposes.

- **db_fresh.sqlite3**: a database with all (current) migrations applied, and a superuser created (see below for credentials)
- **db_default.sqlite3**: a database based on db_fresh, with all default SFU courses preloaded by the API parser.

## NOTE: If you choose to use the databases for your development work, DO NOT modify them directly. Simply rename them to db.sqlite3 and delete when finished

### Superuser credentials

**Username**: admin
**Password**: test
