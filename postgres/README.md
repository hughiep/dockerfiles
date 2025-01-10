# Learning Postgres

## Install

```bash
docker compose up -d
```

## References

- [Postgres Tutorial](https://neon.tech/postgresql/postgresql-getting-started)

## Basic Commands

```bash
# Connect to the database
psql -d dvdrental

# List all databases
\l

# Switch to a different database
\c database_name

# List all tables
\dt

# Describe a table
\d table_name

# Exit psql
\q
```
