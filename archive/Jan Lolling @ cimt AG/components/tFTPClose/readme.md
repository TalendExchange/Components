## <img src='./logo.jpg' width='40' height='40'>tFTPClose

### Overview
Closes a FTP connection (also SFTP the other supported connection types).
Embedded jobs connection to a FTP/SFTP/FTPS Server without closing them can cause serious problems. 
This component is designed to detect the kind of connection beased on the settings of the tFTPConnection component and builds the necessary code to close it correctly.
### Details
* Closes a FTP/SFTP/FTPS connection created by tFTPConnection component
* Avoids a leak of possible connections
### Images
<a href='./screenshots/v_2.0__1.jpg'><img src='./screenshots/v_2.0__1.jpg' ></a>



#### Release Notes

##### 2.0 - 2015-12-02 19:45:44
* Compatible with Talend Open Studio 5.6.2 and 6.x 
* Do not depends on Reflection API anymore
### Compatible
 -  5.0 (obsolete)
 -   5.1 (obsolete)
 -   5.2 (obsolete)
 -   5.3 (obsolete)
 -   5.4 (obsolete)
 -   5.5 (obsolete)
 -   5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)