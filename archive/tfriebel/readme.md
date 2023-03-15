# tfriebel
  <http://blog.dijit.de>
  <nospam+tfriebel@talend.com>

## <a href='./components/tBling/readme.md'><img src='./components/tBling/logo.jpg' width='40' height='40'> tBling</a>
 :warning: Compatibility not known

This component is more a proof of concept than a serious addition to Talend. 
It plays any provided wave file, when executed.
Useful maybe, if you want audio feedback, when a subjob was processed or an error occured.



<img src='./components/tBling/sample.jpg'>

## <a href='./components/tFileOutputJSON/readme.md'><img src='./components/tFileOutputJSON/logo.jpg' width='40' height='40'> tFileOutputJSON</a>
 :warning: Compatibility not known

This component can be used to directly write data into a JSON-file.
JSON is a widely used transportation format in the web 2.0.




<img src='./components/tFileOutputJSON/sample.jpg'>

## <a href='./components/tGSpreadsheetInput/readme.md'><img src='./components/tGSpreadsheetInput/logo.jpg' width='40' height='40'> tGSpreadsheetInput</a>
 :warning: Compatibility not known

tGSpreadsheetInput enables you to read in data from a Google Docs spreadsheet. Therefore it uses the gdata-API provided by Google Inc. whose relevant JARs are included in the component archive.

It requires you to provide a Google-Account username/password. You can then either specifiy the spreadsheet key, or the title. With the key used, the spreadsheet can be accessed directly, where as the title has to be found in the complete list of spreadsheets under your account. The key is the one you can see in the browser address when opening a spreadsheet. To look for the title, uncheck the corresponding checkbox in the components settings.
If you specify a worksheet title (no key here!) you can access the data of the corresponding sheet. If you leave that information empty, the default worksheet within the spreadsheet will be read from.

Attention: The worksheets first row MUST contain the column names. These then have to be used as column names in the schema you define for the tGSpreadsheetInput component. 

The component places itself in the palette under Internet/Google.



<img src='./components/tGSpreadsheetInput/sample.jpg'>
