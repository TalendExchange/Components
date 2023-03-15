## <img src='./logo.jpg' width='40' height='40'>tLOBDownload

### Overview
This component downloads a LOB (BLOB or CLOB) object.
For CLOB content you can set a charset because the CLOBs like BLOBs are always byte streams.
Select in a query the BLOB or CLOB columns and setup for these columns file names where the content have to be downloaded. 
The file names can contains placeholders referring to other columns (e.g. IDs or if the file name is also stored in a column).
### Details
* Works with most database providing CLOBs and BLOBs JDBC compatible.
* Can use the values from other columns in the flow to setup the target file name for a LOB download
### Images
<a href='./screenshots/v_1.2__2.jpg'><img src='./screenshots/v_1.2__2.jpg' ></a>
<a href='./screenshots/v_1.1__1.jpg'><img src='./screenshots/v_1.1__1.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tLOBLoad>Source Code</a>

#### Release Notes

##### 1.1 - 2019-10-27 22:08:29
* compatible with Talend Studio 7.2.x
##### 1.2 - 2020-08-19 09:03:20
* Code cleanup
### Compatible
 -  1.1 (obsolete)
 -  6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2
 - 7.3