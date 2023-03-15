## <img src='./logo.jpg' width='40' height='40'>tSalesforceOutputBulkCustom

### Overview
Allows column overrides to the CSV output.  The allows for such things like parent-key lookups which use dot-notation in the CSV header (which are disallowed for column names due to Java syntax).  The submitted component was extended by using the code fro 5.1 RC1.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-531/screenshot.jpg)
### Images




#### Release Notes

##### 1.0 - 2012-05-21 14:50:04
Allows custom header overrides in the CSV output.  Useful for SalesForce parent-key lookups which use dot notation in (dot notation disallowed for column names due to Java syntax).
##### 1.1 - 2013-01-14 23:22:12
Fixes issue with generated variable names not being unique in some contexts (e.g.  multiple map outputs)
### Compatible
 -  5.1 (obsolete)
 -   5.2 (obsolete)