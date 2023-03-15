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
<a href='./screenshots/v_1.9__2.jpg'><img src='./screenshots/v_1.9__2.jpg' ></a>
<a href='./screenshots/v_1.8__1.jpg'><img src='./screenshots/v_1.8__1.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tDBTableTransfer>Source code</a>

#### Release Notes

##### 1.8 - 2014-08-27 10:19:27
republished and renewed.
##### 1.9 - 2015-02-21 17:33:14
Oracle 12 compatible driver used and icon changed to fit better to the other Oracle components
### Compatible
 -  5.1 (obsolete)
 -   5.4 (obsolete)
 -   5.5 (obsolete)
 -   5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)