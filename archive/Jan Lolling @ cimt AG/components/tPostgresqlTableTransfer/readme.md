## <img src='./logo.jpg' width='40' height='40'>tPostgresqlTableTransfer

### Overview
This component is dedicated to transfer the table content from one database to another database.
The component can truncate the target table before.
This component does not care about schema differences. All columns existing in source and target table will be transferred, all other ignored. The necessary schema will be created internally, therefore you have to provide only the source and target table name, thats it.
The component uses asynchronous transfer to half the duration because reading and writing can take place at the same time (or overlapping).

The component can also be used to export the data as CSV files dedicated to the bulk import.
### Details
* Fast transfer of the data
* Export data in parallel to a bulk input file
* Detects and matches columns to be transferred automatically
### Images
<a href='./screenshots/v_5.3__2.jpg'><img src='./screenshots/v_5.3__2.jpg' ></a>
<a href='./screenshots/v_3.2__1.jpg'><img src='./screenshots/v_3.2__1.jpg' ></a>


### Resources
 * <a href=http://jan-lolling.de/talend/components/help/tPostgresqlTableTransfer.pdf>Documentation</a>
 * <a href=http://sourceforge.net/projects/talend-user-components/>Source Code</a>

#### Release Notes

##### 3.2 - 2016-05-16 19:26:05
* Improved performance
* Improved tolerance for using other source databases
##### 5.3 - 2016-11-26 20:15:34
* Support for PostgreSQL v9.5 with its great insert on conflict command.
* New internal metadata API used
### Compatible
 -  5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)