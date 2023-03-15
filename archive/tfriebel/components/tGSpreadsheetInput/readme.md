## <img src='./logo.jpg' width='40' height='40'>tGSpreadsheetInput

### Overview
tGSpreadsheetInput enables you to read in data from a Google Docs spreadsheet. Therefore it uses the gdata-API provided by Google Inc. whose relevant JARs are included in the component archive.

It requires you to provide a Google-Account username/password. You can then either specifiy the spreadsheet key, or the title. With the key used, the spreadsheet can be accessed directly, where as the title has to be found in the complete list of spreadsheets under your account. The key is the one you can see in the browser address when opening a spreadsheet. To look for the title, uncheck the corresponding checkbox in the components settings.
If you specify a worksheet title (no key here!) you can access the data of the corresponding sheet. If you leave that information empty, the default worksheet within the spreadsheet will be read from.

Attention: The worksheets first row MUST contain the column names. These then have to be used as column names in the schema you define for the tGSpreadsheetInput component. 

The component places itself in the palette under Internet/Google.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-122/screenshot.jpg)
### Images




#### Release Notes

##### 0.1 - 2009-02-20 14:39:48
Tested with TIS 3.0.2 and TOS 3.0.2 and 3.0.3


### Compatible
 -  3.0 (obsolete)