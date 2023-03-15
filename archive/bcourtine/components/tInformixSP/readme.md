## <img src='./logo.jpg' width='40' height='40'>tInformixSP

### Overview
Informix stored procedure

This component allows to use Informix stored procedures and functions.

Not existing in origanal Informix components. 

Can be used with an existing tInformixConnection.

This component has been improved and added to TOS 4.0.0+. So it is now supported on Talend bugtracker.
### Images




#### Release Notes

##### 0.1 - 2009-03-27 13:28:06
First revision of this component.

This component needs an updated Informix JDBC driver (provided in version 0.3 and above of tInformixInput component).

This revision is UNSTABLE : if you check the "is function" checkbox, there will be a runtime error.
You can use this component to execute Informix stored functions by setting a recordset param. The recordset will contain the function return.

This bug will be corrected in a future release.

I tested this component on TOS 3.1.0M1 and it does NOT work.
##### 0.2 - 2009-05-06 10:59:38
- Family information added for 3.1.0 compatibility
- French translation of the component
- Cleaning of translation files to remove unused keys

This version is NOT compatible anymore with 3.0.X versions of Talend Open Studio

The "is function" checkbox of this component does not work yet. This problem will be corrected in a future version.

03/06/2009 : correction of a 3.1.X compatibility problem
### Compatible
 -  3.0 (obsolete)
 -   3.1 (obsolete)