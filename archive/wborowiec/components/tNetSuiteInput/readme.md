## <img src='./logo.jpg' width='40' height='40'>tNetSuiteInput

### Overview
The tNetSuiteInput component allows you to read and search NetSuite records via the NetSuite web services API.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-353/screenshot.jpg)
### Images




#### Release Notes

##### 0.3 - 2011-06-03 18:28:23
0.2 - Added Boolean to the list of supported search operators.
0.3 - Fixed a bug with no search criteria creating a null pointer exception
##### 0.4.3 - 2011-10-05 20:28:06
0.4.3
- Fixed InternalId search issue

0.4.1
- Fixed component naming problem

0.4:
- Support for custom fields (in the criteria and in the results)
- Added Date to the list of supported search operators
- Fixed Transaction searches, and added support for PurchaseOrders
- Added the Body fields only checkbox, that allows to fetch only transaction body fields, or to fetch line items as well

0.3:
- Fixed a bug with no search criteria creating a null pointer exception

0.2:
- Added Boolean to the list of supported search operators
- Support for NetSuite searches with multiple criteria

Additional resources:
- Demo Project: http://ht.ly/6O8CP 
- Walk trough: http://ht.ly/6O985
##### 0.5 - 2011-11-23 15:48:20
0.5.0:
- Plugin structure rebuild
- Javajet rebuilt
- Plugin renamed with capital S
- Added Between and NotBetween search operator support
- Restricted the WSDL to the 2011_1 version for sandbox, production and beta
- Added die on error option
- Fixed bug when searching for empty value
- Added request level authentication
- Added support for Multi and Enum type search
\t* Just enter in the Value column of the Search table the values separated by a comma.
\t* To search for multiple: \\\\\\"4\\\\\\",\\\\\\"2\\\\\\",\\\\\\"5\\\\\\"
- Added support for CustomRecord search
- Added support for joined search

Known issue:
- Some Item types are missing
- Opportunity is Transaction only
- Some field in TransactionJoin are searchable but not available for the associated record
- When migrating from previous version, you need to change workspace and reinitialize the Generation Engine (Ctrl+Shift+F3)

Note:
- InternalId or ExternalId field is a List type field (i.e: SearchMultiSelectField), you need to use the related operator such as List - AnyOf or List - NoneOf

0.4.2:
- Fixed InternalId search issue

0.4.1
- Fixed component naming problem

0.4.0:
- Support for custom fields (in the criteria and in the results)
- Added Date to the list of supported search operators
- Fixed Transaction searches, and added support for PurchaseOrders
- Added the Body fields only checkbox, that allows to fetch only transaction body fields, or to fetch line items as well

0.3.0:
- Fixed a bug with no search criteria creating a null pointer exception

0.2.0:
- Added Boolean to the list of supported search operators
- Support for NetSuite searches with multiple criteria

Additional resources:
- Demo Project: http://ht.ly/6O8CP 
- Walk trough: http://ht.ly/6O985
##### 0.5.1 - 2011-11-24 19:51:09
0.5.1:
- Fix CustomRecord search issue. The Text field was no longer visible to set the ID of the Record.

0.5.0:
- Plugin structure rebuild
- Javajet rebuilt
- Plugin renamed with capital S
- Added Between and NotBetween search operator support
- Restricted the WSDL to the 2011_1 version for sandbox, production and beta
- Added die on error option
- Fixed bug when searching for empty value
- Added request level authentication
- Added support for Multi and Enum type search
\t* Just enter in the Value column of the Search table the values separated by a comma.
\t* To search for multiple: \\"4\\",\\"2\\",\\"5\\"
- Added support for CustomRecord search
- Added support for joined search

Known issue:
- Some Item types are missing
- Opportunity is Transaction only
- Some field in TransactionJoin are searchable but not available for the associated record
- When migrating from previous version, you need to change workspace and reinitialize the Generation Engine (Ctrl+Shift+F3)

Note:
- InternalId or ExternalId field is a List type field (i.e: SearchMultiSelectField), you need to use the related operator such as List - AnyOf or List - NoneOf

0.4.2:
- Fixed InternalId search issue

0.4.1
- Fixed component naming problem

0.4.0:
- Support for custom fields (in the criteria and in the results)
- Added Date to the list of supported search operators
- Fixed Transaction searches, and added support for PurchaseOrders
- Added the Body fields only checkbox, that allows to fetch only transaction body fields, or to fetch line items as well

0.3.0:
- Fixed a bug with no search criteria creating a null pointer exception

0.2.0:
- Added Boolean to the list of supported search operators
- Support for NetSuite searches with multiple criteria

Additional resources:
- Demo Project: http://ht.ly/6O8CP 
- Walk trough: http://ht.ly/6O985
##### 0.5.2 - 2011-12-08 20:42:23
0.5.2:
- Fix issue when activating joined search without defining any criteria.

0.5.1:
- Fix CustomRecord search issue. The Text field was no longer visible to set the ID of the Record.

0.5.0:
- Plugin structure rebuild
- Javajet rebuilt
- Plugin renamed with capital S
- Added Between and NotBetween search operator support
- Restricted the WSDL to the 2011_1 version for sandbox, production and beta
- Added die on error option
- Fixed bug when searching for empty value
- Added request level authentication
- Added support for Multi and Enum type search
\t* Just enter in the Value column of the Search table the values separated by a comma.
\t* To search for multiple: \\"4\\",\\"2\\",\\"5\\" (You do not have to add slashes, Talend exchange add the slashes as escape characters)
- Added support for CustomRecord search
- Added support for joined search

Known issue:
- Some Item types are missing
- Opportunity is Transaction only
- Some field in TransactionJoin are searchable but not available for the associated record
- When migrating from previous version, you need to change workspace and reinitialize the Generation Engine (Ctrl+Shift+F3)

Note:
- InternalId or ExternalId field is a List type field (i.e: SearchMultiSelectField), you need to use the related operator such as List - AnyOf or List - NoneOf

0.4.2:
- Fixed InternalId search issue

0.4.1
- Fixed component naming problem

0.4.0:
- Support for custom fields (in the criteria and in the results)
- Added Date to the list of supported search operators
- Fixed Transaction searches, and added support for PurchaseOrders
- Added the Body fields only checkbox, that allows to fetch only transaction body fields, or to fetch line items as well

0.3.0:
- Fixed a bug with no search criteria creating a null pointer exception

0.2.0:
- Added Boolean to the list of supported search operators
- Support for NetSuite searches with multiple criteria

Additional resources:
- Demo Project: http://ht.ly/6O8CP 
- Walk trough: http://ht.ly/6O985
### Compatible
 -  4.0 (obsolete)
 -   4.1 (obsolete)
 -   4.2 (obsolete)
 -   5.0 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)