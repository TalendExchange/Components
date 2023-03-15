## <img src='./logo.jpg' width='40' height='40'>tDB2TableTransfer

### Overview
This component is dedicated to transfer the table content from one database to another database.
The component can truncate the target table before.
This component does not care about schema differences. All columns existing in source and target table will be transferred, all other ignored. The necessary schema will be created internally, therefore you have to provide only the source and target table name, thats it.
The component uses asynchronous transfer to half the duration because reading and writing can take place at the same time (or overlapping).


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-1348/screenshot.jpg)
### Images




#### Release Notes

##### 9.6 - 2021-12-09 14:20:17
* Fetch column names from select with alias works now correctly
* Set Date typed value for fix column values does not need the manual conversion from java.util.Date to java.sql.Date
### Compatible
 - 6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2
 - 7.3
 - 8.0