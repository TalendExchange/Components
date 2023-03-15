## <img src='./logo.jpg' width='40' height='40'>tMysqlConnectionPool

### Overview
This is an implementation of the Apache DBCP2 pool project for MySQL. It provides in a normal DI job the possibility to use a DataSource.
This is a great advantage for jobs which needs a database connection in a rapidely called embedded job. 
The pool has all the necessary features we expect today.
### Details
* Can be used in normal DI jobs
* Can greatly improve the DataSource handling in DI jobs - also for DI made services
* Has a lot of features to take care of the health of the connections
### Images
<a href='./screenshots/v_2.8__2.jpg'><img src='./screenshots/v_2.8__2.jpg' ></a>
<a href='./screenshots/v_2.8__1.jpg'><img src='./screenshots/v_2.8__1.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tDatabaseConnectionPool>Source Code on Github</a>
 * <a href=http://jan-lolling.de/talend/components/help/tPostgresqlConnectionPool.pdf>Documentation</a>

#### Release Notes

##### 2.8 - 2021-12-14 14:55:46
* Log4J removed
### Compatible
 - 6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2
 - 7.3
 - 8.0