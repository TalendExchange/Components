## <img src='./logo.jpg' width='40' height='40'>tOracleTableTransfer

### Overview
This component is dedicated to transfer the table content from one database to another database.
The component can truncate the target table before.
This component does not care about schema differences. 
All columns existing in source and target table will be transferred, all other ignored. The necessary schema will be created internally, therefore you have to provide only the source and target table name, thats it.
The component uses asynchronous transfer to (up to) halve the duration because reading and writing can take place at the same time (or overlapping).
### Details
* schemaless transfer of table data.
* read and write in parallel
* Source database can be any other database type beside Oracle
* Can exclude columns from transfer
* Can include new columns (filled with fixed values)
### Images
<a href='./screenshots/v_3.2__1.jpg'><img src='./screenshots/v_3.2__1.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tDBTableTransfer>Source code</a>

#### Release Notes

##### 3.2 - 2016-10-20 14:29:58
* Updated transfer engine - runs now faster
* Feature added: backup file can be created
### Compatible
 -  5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)
 -   6.4 (obsolete)
 -  6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)