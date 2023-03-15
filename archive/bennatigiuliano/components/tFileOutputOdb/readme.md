## <img src='./logo.jpg' width='40' height='40'>tFileOutputOdb

### Overview
This component allows you to execute an Insert into SQL tables on OpenOffice.org database files (.odb) Adding of functionnalities : Update/Delete based on keys columns to define Sql Where clauses, + a cleaning function when .odb file is corrupted by a Sql error.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-404/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2011-08-29 10:18:38
tFileOutputOdb : The tFileOutputOdb component allows you to perform delete* then insert into SQL tables on OpenOffice.org database files (.odb)
##### 0.2 - 2011-09-12 06:20:32
This component allows you to execute an insert into SQL tables on OpenOffice.org database files (.odb)

Pease, set schema columns number to your targeted tables
##### 0.3 - 2011-10-20 07:53:39
This component allows you to execute an Insert into SQL tables on OpenOffice.org database files (.odb)  Adding of functionnalities : Update/Delete based on keys columns to define Sql Where clauses, + a cleaning function when .odb file is corrupted by a Sql error.
##### 0.4 - 2012-03-14 11:43:40
This component allows you to execute an Insert, Update/Delete (based on keys columns to define Sql Where clauses) into SQL tables on OpenOffice.org database files (.odb), + a cleaning function when .odb file is corrupted by a Sql error.
This minor correction giving an increase of line\\'s number written in .odb from 200 lines/sec to 8000 lines/sec. 
##### 0.5 - 2014-10-17 07:22:03
With OOo V4 it seems to me hsqldb give verbose I haven\\'t seen before as : 

[INFO ]: hsqldb.db.HSQLDB491CF4B266.ENGINE - open start - state not modified
[INFO ]: hsqldb.db.HSQLDB491CF4B266.ENGINE - dataFileCache open start
[INFO ]: hsqldb.db.HSQLDB491CF4B266.ENGINE - dataFileCache open end
[INFO ]: hsqldb.db.HSQLDB491CF4B266.ENGINE - Checkpoint start
[INFO ]: hsqldb.db.HSQLDB491CF4B266.ENGINE - checkpointClose start
[INFO ]: hsqldb.db.HSQLDB491CF4B266.ENGINE - dataFileCache commit start
[INFO ]: hsqldb.db.HSQLDB491CF4B266.ENGINE - dataFileCache commit end
[INFO ]: hsqldb.db.HSQLDB491CF4B266.ENGINE - checkpointClose end
[INFO ]: hsqldb.db.HSQLDB491CF4B266.ENGINE - Checkpoint end - txts: 31

And I\\'ve find a trouble with \\"set commit true\\" instruction. So I commented It now.

### Compatible
 -  4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   5.5 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)