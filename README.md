# Psql_CLI
Command with Psql_CLI to manage databases

Psql take a schema like a 'class' to define all data tables 

## Instructions to run CLI with Psql
  - Go to local disk c
  - Program files\Postgres\:version\bin
  - execute the command psql -U postgres -h localhost 
  - Create your database
  - Create your tables

## Commands 
  - \c $dbname	Connect to database $dbname.	\c blog_development
  - \d	Describe available relations	
  - \d $name Describe relation $name	\d users
  - \?	List of console commands and options	
  - \h	List of available SQL syntax Help topics	
  - \h $topic	SQL syntax Help on syntax for $topic	\h INSERT
  - \q	Quit	