## <img src='./logo.jpg' width='40' height='40'>tSchemaComplianceCheckRegex

### Overview
use regex with tSchemaComplianceCheck (extend tSchemaComplianceCheck)

beta version : test in 3.2 TOS

Uitlisation :
Check "use regex"
use pattern or a static Class Pattern routines as a library.
leave field empty if no regex 

preferences :
use with Pattern looks like
// template routine Java
package routines;


public class Pattern {
\tstatic public String insee = "^[12][0-9]{2}(0[1-9]|1[0-2])(2[AB]|[0-9]{2})[0-9]{6}([0-9]{2})?$";
\tstatic public String phone_fr = "^0[1-689]([-. ]?[0-9]{2}){4}$";
\tstatic public String email = "[a-zA-Z0-9._%-]+@[a-zA-Z0-9.-]+\\.[a-zA-Z]{2,4}";
}


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-215/screenshot.jpg)
### Images




#### Release Notes

##### 0.12 - 2009-11-17 15:56:26
return null value for all field in TOS < 3.2 (!?)
### Compatible
 -  3.2 (obsolete)