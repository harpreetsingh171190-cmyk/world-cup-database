cat << 'EOF' > README.md
# World Cup Database

This project is part of freeCodeCamp's Relational Database Certification. It features a PostgreSQL database containing World Cup match statistics, a Bash automation script for data insertion, and a collection of complex SQL queries.

## Project Structure
- `worldcup.sql`: The complete PostgreSQL database dump.
- `insert_data.sh`: A Bash script that reads `games.csv` and dynamically populates the `teams` and `games` tables.
- `queries.sh`: A Bash script containing SQL queries to extract key statistics from the database.
EOF
