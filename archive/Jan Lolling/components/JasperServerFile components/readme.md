## <img src='./logo.jpg' width='40' height='40'>JasperServerFile components

### Overview
These component provide the capabilties to handle files on the JasperServer.
They use now the rest-v2 interface and therefore compatible with the current releases of the JaspeServer.
You can do all typical file operations with them.
A typical use case is to send offline generated report result files on a JasperServer.

There are following components
tJasperServer - provides the connection to the JasperServer to share it over multiple components
tJasperServerFilePut - Put a file in the repository
tJasperServerFileGet - Get a file from the repository
tJasperServerFileDelete - Delete a file from the repository
tJasperServerFileCopy - Copy/move a file within the repository
tJasperServerFileList - List files in the repository
tJasperServerClose - Close the explicit connection created by tJasperServer component
### Details
* Enhance the reporting content in the JasperServer with external generated files (e.g. with Talend jobs generated Excel files)
* Put, get, delete, list, copy or move files
### Images
<a href='./screenshots/v_2.7__25.jpg'><img src='./screenshots/v_2.7__25.jpg' ></a>
<a href='./screenshots/v_2.7__24.jpg'><img src='./screenshots/v_2.7__24.jpg' ></a>
<a href='./screenshots/v_2.7__23.jpg'><img src='./screenshots/v_2.7__23.jpg' ></a>
<a href='./screenshots/v_2.7__22.jpg'><img src='./screenshots/v_2.7__22.jpg' ></a>
<a href='./screenshots/v_2.7__21.jpg'><img src='./screenshots/v_2.7__21.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tJasperServerFile/blob/master/doc/tJasperServerFileCopy.pdf>Documentation tJasperServerFileCopy</a>
 * <a href=https://github.com/jlolling/talendcomp_tJasperServerFile>Source Code</a>
 * <a href=https://github.com/jlolling/talendcomp_tJasperServerFile/blob/master/doc/tJasperServerFileDelete.pdf>Documentation tJasperServerFileDelete</a>
 * <a href=https://github.com/jlolling/talendcomp_tJasperServerFile/blob/master/doc/tJasperServerFilePut.pdf>Documentation tJasperServerFilePut</a>
 * <a href=https://github.com/jlolling/talendcomp_tJasperServerFile/blob/master/doc/tJasperServerFileList.pdf>Documentation tJasperServerFileList</a>
 * <a href=https://github.com/jlolling/talendcomp_tJasperServerFile/blob/master/doc/tJasperServerFileGet.pdf>Documentation tJasperServerFileGet</a>

#### Release Notes

##### 2.0 - 2019-10-11 14:23:55
* Use the REST interface v2 and is now compatible with the latest JasperServer releases
* Improved performance
* All components at once in a package
##### 2.1 - 2019-10-16 07:04:58
* Close functionality added: implicit in the components and as dedicated new component tJasperServerClose
##### 2.3 - 2019-10-22 20:20:59
* Bug fixed: ZIP and Excel files are not uploaded correctly. These file type was damaged by adding the http header to the actual file content.
* Bug fixed: modules not loaded in Talend 7.2.1
##### 2.6 - 2020-05-06 08:58:44
* error handling improved
* http client lib updated
##### 2.7 - 2020-05-10 19:16:58
* Prevent Exception while list an empty folder in the server repository
### Compatible
 -  6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)
 -   6.4 (obsolete)
 -  6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2
 - 7.3