# Periodic Table Database

PostgreSQL database for chemical elements with bash query script.

## Files
- element.sh – query elements by atomic number, symbol, or name
- periodic_table.sql – full database dump

## Usage
```bash
psql -U postgres < periodic_table.sql   # load DB
./element.sh 1                          # query Hydrogen
./element.sh H
./element.sh Hydrogen
