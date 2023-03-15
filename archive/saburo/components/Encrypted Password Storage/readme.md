## <img src='./logo.jpg' width='40' height='40'>Encrypted Password Storage

### Overview
pwdStore is a set of routines that can help in managing passwords (db connections, ftp etc) or other strings used as parameters in TOS jobs.
By default, passwords in the repository or in the component parameters are stored by talend as plain text and become visible constants in the generated java source code. 
It is common practice to have an external configuration file to ease the deployment in different environments with different accounts/urls/ etc, however there is no standard functionality to have those file encrypted.

This set of simple methods use a java library that leverages java.crypto to read and write strings in encrypted files.   


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-388/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2011-06-09 07:05:57
First public release
### Compatible
 -  4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)