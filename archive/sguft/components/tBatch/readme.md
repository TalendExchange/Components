## <img src='./logo.jpg' width='40' height='40'>tBatch

### Overview
tBatch allows you to perform a subtask in batches.

Eg. fetch and write 10.000 records at a time from one database table into another.

This is very useful when you want to prevent memory issues that occur when Talend are handling too many records at a time (eg. if you try to load and process 10 mio. rows).

Unfortunately Talend Exchange does only allow me to upload 1 screenshot, so to see how to do the entire process please visit these links:

http://innonova.dk/talend/batch_1.jpg
http://innonova.dk/talend/batch_2.jpg
http://innonova.dk/talend/batch_3.jpg


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-571/screenshot.jpg)
### Images




#### Release Notes

##### 1.0 - 2012-06-21 09:55:33
tBatch allows you to perform subtasks in batches (eg. database reads and wirtes)
##### 1.1 - 2012-06-25 14:00:07
- You can now specify a max number of rows to return for the batch process, so when debug-running a job, you don\\\\\\'t have to process all 10 mio. rows.
- Debug output now defaults to false
##### 1.2 - 2012-08-07 08:06:28
Improved the batching process - see attached images
### Compatible
 -  4.2 (obsolete)
 -   5.0 (obsolete)
 -   5.1 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)