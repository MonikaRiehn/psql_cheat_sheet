# psql Cheat Sheet

## Running postgreSQL queries from the Linux command line

`psql -U postgres postgres` or `psql -d database_name -U user_name` start psql in the command line

`\c database_name` connect with database -> You are now connected to database "database_name" as user "user_name". `database_name-#...`

