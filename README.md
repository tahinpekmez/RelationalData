#What You Will build
I will build an application that uses Spring’s JdbcTemplate to access data stored in a relational database.

# After Build

***You will see:***

```console
2019-09-26 13:46:58.561  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Creating tables
2019-09-26 13:46:58.564  INFO 47569 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2019-09-26 13:46:58.708  INFO 47569 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Start completed.
2019-09-26 13:46:58.809  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Inserting customer record for John Woo
2019-09-26 13:46:58.810  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Inserting customer record for Jeff Dean
2019-09-26 13:46:58.810  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Inserting customer record for Josh Bloch
2019-09-26 13:46:58.810  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Inserting customer record for Josh Long
2019-09-26 13:46:58.825  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Querying for customer records where first_name = 'Josh':
2019-09-26 13:46:58.835  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Customer[id=3, firstName='Josh', lastName='Bloch']
2019-09-26 13:46:58.835  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Customer[id=4, firstName='Josh', lastName='Long']
```