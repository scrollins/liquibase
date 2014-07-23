Liquibase Project  Refer to http://www.liquibase.org/documentation/maven for allMaven targets

1.Create schema on mysql called demo
2.Run mvn liquibase:update   This will create a deal table and insert data

mvn liquibase:dropAll will remove all ddl changes 
