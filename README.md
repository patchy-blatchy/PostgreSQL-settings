# PostgreSQL-settings
Create new user with all permissions and database to the PostgreSQL on mac:
```
createuser -P user_name
createdb db_name
psql db_name
grant all privileges on database db_name to user_name;
```
