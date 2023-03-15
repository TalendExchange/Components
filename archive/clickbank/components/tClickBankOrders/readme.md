## <img src='./logo.jpg' width='40' height='40'>tClickBankOrders

### Overview
A component to aid in the development of accessing the ClickBank Orders Api.  To use the ClickBank api, you must have a vendor or affiliate account at ClickBank, and you must create api developer and clerk keys.  The component has all the orders api methods readily available, and allows you to add parameters in a table.  The output includes three variables in one row.  The first is request body, which is formated in json or xml, depending on which output type you select. The second is an error string if one exists, and the third is the http status code.  To learn more about the ClickBank Orders api and the methods available please visit: http://www.clickbank.com/help/account-help/account-tools/clickbank-api/

For a list of methods represented in the Method drop down see:
https://api.clickbank.com/rest/1.2/orders


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-315/screenshot.jpg)
### Images




#### Release Notes

##### 1.0 - 2010-08-24 15:46:41
Component to send a request message to ClickBank Orders API and output the response and http status code in a normal row output.
##### 1.1 - 2010-08-24 23:07:07
[lang=en]This revision has a fix to urlencode the get parameters using java.net.URLEncoder.encode.[/lang]
### Compatible
 -  4.0 (obsolete)
 -   4.1 (obsolete)