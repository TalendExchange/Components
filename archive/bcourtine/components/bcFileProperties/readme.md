## <img src='./logo.jpg' width='40' height='40'>bcFileProperties

### Overview
This components based on tFileProperties gives more information : file owner, file permissions, etc.

WARNING: this new information comes from the Java 7 NIO2 API. So, this component only works in a Java 7 environment.
### Images




#### Release Notes

##### 0.1 - 2011-10-31 08:22:45
First revision, with the file owner and the file permissions informations.
##### 0.2 - 2012-05-22 15:02:04
Release notes :
- the file hash method can be chosen (MD2, MD5, SHA-1, etc.)
- mtime_string is removed
- mode_string is replaced by 3 properties (is_readable, is_writable, is_executable)
- ctime (creation time) and atime (last access time) properties are added
- is_hidden is added
- is_symolic is added
- bug correction: posix file permission are calculated only on no-Windows OS to prevent a runtime exception on Windows.
### Compatible
 -  4.0 (obsolete)
 -   4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   5.1 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)