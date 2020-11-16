# Satellite Database foo

## Backups

## Interacting with DB (postgres)
NOTE:  This will absolutely void your warranty/support.  So, be careful, don't do anything (other than look around) unless support advises you to.

```
su - postgres
psql
# List Database
\l 
# Change DB
\c foreman
# List Tables
\dt 
# Select all the rows from the domains tables
select * from domains;
# Quit
\q
```

