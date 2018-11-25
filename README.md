# schemology
Coursemology ERD

1. Get Schemaspy:
https://github.com/schemaspy/schemaspy/releases

2. Get latest Postgres JDBC driver:
https://jdbc.postgresql.org/download.html

3. Command line:
java -jar schemaspy-6.0.0-rc2.jar -dp postgresql-42.2.5.jar -t pgsql -host localhost -db coursemology_dev -u [your_username] -o ./schemology -s public
