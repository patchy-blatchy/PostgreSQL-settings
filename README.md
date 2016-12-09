# PostgreSQL-settings

Create new user with password and all permissions: 
```
$ su - postgres 
$ psql template1
template1=# CREATE USER tester WITH PASSWORD 'test_password';
template1=# GRANT ALL PRIVILEGES ON DATABASE "test_database" to tester;
template1=# \q
```
