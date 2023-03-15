## <img src='./logo.jpg' width='40' height='40'>tFlowToSapRfcTable

### Overview
Prepares a flow to pass it as a table parameter to a SAP RFC Function Module

To use this component, you have to put it after a flow output and before a SAP-Component like tSAPInput which calls an RFC-Function Module where you have to pass a table parameter. 

In the SAP-Component at "Initialize Input" insert "globalMap.get(COLUMNNAME)" 
where COLUMNNAME is the name of the current column in upper case letters!


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-738/screenshot.jpg)
### Images




#### Release Notes

##### 1.0 - 2013-01-04 08:29:20
I could only test it on version  5.1.1 of Talend, but it should run also on others!
### Compatible
 -  5.1 (obsolete)