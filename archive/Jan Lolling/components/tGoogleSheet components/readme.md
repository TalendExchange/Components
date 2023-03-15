## <img src='./logo.jpg' width='40' height='40'>tGoogleSheet components

### Overview
* supports service accounts as well as application-client-ID as authentication method (2-factor)

tGoogleSheetInput
* has capabilities to configure the correct column position by the header line
* can parse dates tolerant

tGoogleSheetOutput
* Can create Google Sheet documents
* Can create sheets
* write into sheets

To read or write into existing documents these components expects the File-ID. To get this use tGoogleDrive (from Talend Exchange) or the build-in tGoogleDriveList (with less funtionality).
### Details
* Service account or Application-Client-ID usable as authentication method
* Configure columns by the header row
* Tolerant Date parser used
* Create or use existing documents
### Images
<a href='./screenshots/v_4.1__12.jpg'><img src='./screenshots/v_4.1__12.jpg' ></a>
<a href='./screenshots/v_4.1__11.jpg'><img src='./screenshots/v_4.1__11.jpg' ></a>
<a href='./screenshots/v_4.1__10.jpg'><img src='./screenshots/v_4.1__10.jpg' ></a>
<a href='./screenshots/v_4.0__9.jpg'><img src='./screenshots/v_4.0__9.jpg' ></a>
<a href='./screenshots/v_4.0__8.jpg'><img src='./screenshots/v_4.0__8.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tGoogleSheet>Source code</a>
 * <a href=https://github.com/jlolling/talendcomp_tGoogleSheet/releases/download/1.0/tGoogleSheet.pdf>Documentation</a>

#### Release Notes

##### 2.1 - 2017-06-03 10:08:27
* Guave lib updated to prevent incompatibility with Google AdWords component
##### 3.0 - 2018-01-01 00:11:11
* tGoogleSheetOutput can write header row
##### 4.0 - 2020-11-10 18:51:49
* tGoogleSheetOutput improved: option added to take the input values just like the user would enter them in Google Sheets directly
* Dependency to log4j v1 replaced by using sl4j framework
* Updated Google APIs
##### 4.1 - 2021-01-28 10:23:27
* Improved check of type of authentication credentials
* Updated Google Sheet API
### Compatible
 - 6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2
 - 7.3