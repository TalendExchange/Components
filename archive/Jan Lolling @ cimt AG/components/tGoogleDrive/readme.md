## <img src='./logo.jpg' width='40' height='40'>tGoogleDrive

### Overview
This component manages files and folders on a Google Drive via the Google Drive API v2.
It has various operational modes to:
- upload a file (also with set permissions to other users)
- download a file
- list files (with filtering)
- get the properties of a file/folder
- move files
- delete files

Especially for the usage in conjunction with tGoogleAnalyticsUnsampledReports this component provides the same authentication methods as for the Google Analytics and is able to work directly with file-Ids.
   
Please refer the linked documentation.
For questions and suggestions please contact me: jan.lolling@gmail.com
Please do not use the rating function to post questions.
### Details
* Connect to Google Drive with Client-ID or a Service Account.
* Address files by their document-ID or the label.
* Put, update, get, move, copy, delete, list files
* Add permissions to uploaded files.

### Images
<a href='./screenshots/v_2.1__2.jpg'><img src='./screenshots/v_2.1__2.jpg' ></a>
<a href='./screenshots/v_2.0__1.jpg'><img src='./screenshots/v_2.0__1.jpg' ></a>


### Resources
 * <a href=http://jan-lolling.de/talend/components/help/tGoogleDrive.pdf>Documentation</a>
 * <a href=http://sourceforge.net/projects/talend-user-components/>Source Code</a>
 * <a href=http://jan-lolling.de/talend/howtos/google_service_account/create-a-google-service-account.html>How to create a Google service account</a>

#### Release Notes

##### 2.0 - 2015-11-25 17:27:30
* Improved error handling, the component can retry requests in particular error situations
* Bug fix: Code generation fails in case of the option "Reuse Client" is switch off
* New release of the Google Drive API used
##### 2.1 - 2015-12-18 18:08:58
* updated Google APIs used
### Compatible
 -  5.3 (obsolete)
 -   5.4 (obsolete)
 -   5.5 (obsolete)
 -   5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)