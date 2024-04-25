# Install PostgreSQL in Linux/Ubuntu in GCP,Azure,AWS

Relational database management systems are a key component of many web sites and applications. They provide a structured way to store, organize, and access information. PostgreSQL is a relational database management system that provides an implementation of the SQL querying language. It’s standards-compliant and has many advanced features like reliable transactions and concurrency without read locks.

This guide demonstrates how to quickly get Postgres up and running on an Ubuntu server, from installing PostgreSQL to setting up a new user and database.
As a pre-requisites your server should have a non-root user with sudo permissions and a basic firewall.

#Step-1 Installing PostgreSQL
Ubuntu’s default repositories contain Postgres packages, so you can install these using the apt packaging system.

__sudo apt update__

Then, install the Postgres package along with a -contrib package that adds some additional utilities and functionality:

__sudo apt install postgresql postgresql-contrib__

Ensure that the server is running using the systemctl start command:

__sudo systemctl start postgresql.service__

# Using PostgreSQL Roles and Databases

__sudo -i -u postgres__

__psql__

__\q__
