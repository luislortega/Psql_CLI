# Psql_CLI
Command with Psql_CLI to manage databases

Psql take a schema like a 'class' to define all data tables 

## Instructions to run CLI with Psql
  - Go to local disk c
  - Program files\Postgres\:version\bin
  - execute the command psql -U postgres -h localhost 
  - Create your database
  - Create your tables

## Commands to...
- **Create a database:**
    - create database :name; 
    - to switch database \c databaseName
- **Show:**
    - databases: \l 
    - roles: \du
    - tables: \d schema.table || \dt
    - schemas: \dn
- **Create:**
    - roles: create user *bob* with password '*mypass*';
    - schemas: create schema *friends*;
    - tables: create table *friends*.*test*(firstname CHAR(15), lastname CHAR(15));
- **Insert:**
    - insert into *friends*.*test*('Luis Gerardo', 'Leon Ortega');
- **Select**
    - select * from *friends*.*test*;