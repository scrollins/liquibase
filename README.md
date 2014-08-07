Liquibase using Maven  For full documentation go to http://www.liquibase.org/documentation/maven/
=========

Make sure you have MySql installed. 

1. Run mvn sql:execute .   This will create/drop 'market' schema
2. Run mvn liquibase:update.  This will create a deal table and insert data. 



