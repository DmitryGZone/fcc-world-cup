# World Cup Database

This project is part of the freeCodeCamp Relational Database certification.

It includes:
- PostgreSQL database dump (`worldcup.sql`)
- Bash script to insert data (`insert_data.sh`)
- Bash script with SQL queries (`queries.sh`)

## Restore the database

```bash
psql -U postgres < worldcup.sql
