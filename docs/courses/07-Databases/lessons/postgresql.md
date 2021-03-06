PostgreSQL

### PostgreSQL Commands
  
Lists all the commands you can run from PostgreSQL

`\h`

Quits PostgreSQL

`\q`

Connects to a specific database

`\c database_name`

List tables in the database you are connected to

`\dt`

This command creates a database

`create database database_name;`

List all the rows in content of a specific table

`select * from table_name;`

This command select a specific value in the table

`select * from table_name where field_name = ‘value’`

This command selects a value in the table that is a full or partial match for the value

`select * from table_name where field_name like ‘value%’`


### PostgreSQL Commands Continued

This command updates a specific value in the table with a new value

`update table_name set table_row_name = 'new_value' where table_row_name = 'old_value';`

This command updates a specific value in the table with a new value

`update table_name set table_row_name = 'new_value' where table_row_name like 'old_value%';`

This command deletes a specific entry from the table

`delete from table_name where row_name = 'value';`
