# Lucian DRAGOMIR
  <nospam+lucian.dragomir@gmail.com>

## <a href='./components/tFTPDirectoryExist/readme.md'><img src='./components/tFTPDirectoryExist/logo.jpg' width='40' height='40'> tFTPDirectoryExist</a>
 :warning: Compatibility not known

This component can be used to test if a directory exists on a ftp or a sftp host. The component was tested using Talend Open Studion 6.1.0 but it should work with any talend version.

In case of FTP connections (that are using com.enterprisedt.net.ftp.FTPClient) there is no support for testing the existence of a directory so the component tries to change directory to the requested one and then to change back to the previous current.
<img src='./components/tFTPDirectoryExist/sample.jpg'>
