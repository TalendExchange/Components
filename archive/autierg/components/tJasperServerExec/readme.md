## <img src='./logo.jpg' width='40' height='40'>tJasperServerExec

### Overview
This component executes a report from JasperServer's repository (compatible with JasperServer CE , PRO and ENTERPRISE). The component uses webservices to access repository and get reports.You can manage report's parameters as well.
No XML configuration, no temporary csv datasource. This component really is simple to use.



![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-253/screenshot.jpg)
### Images




#### Release Notes

##### 0.21 - 2010-01-27 10:11:49
Notes :
-------
Fixed a bug with destination bath (users had to add '/' manually)
Automatically adds the extention to the file name according to the export type

Known limitations :
------------------
- exports only on pdf
- can handle only string parameters
Those will be fixed in next releases
##### 0.3 - 2010-02-04 11:16:05
Version 0.3 :
------------
Added exports formats for xls,rtf,html,csv,odt
Added options for csv format (Encoding type and Row separator)

Known Limitation :
-----------------
Parameters can only be strings

This will be fixed in next releases
##### 4.0 - 2011-03-03 15:52:33
This component uses JasperReportsServer's webservices to generates reports.
This have been updated to be used JasperReportsServer's versions 4.0 (both CE and PRO)

Now the releases will follow the same version number than the server to avoid confusions.
##### 4.1.2 - 2011-10-03 15:02:40
This component uses JasperReportsServer\\'s webservices to generates reports.
This have been updated to be used JasperReportsServer\\'s versions 4.2.x (both CE and PRO as they are using JR 4.1.x)

Now the releases versions will folow the same numbers as the JasperReports library.

The component have been tested with TOS 4.2.x versions.
Be sure to use this component with 4.2.x versions of TOS and JETL
### Compatible
 -  3.0 (obsolete)
 -   3.1 (obsolete)
 -   3.2 (obsolete)
 -   4.0 (obsolete)
 -   4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)