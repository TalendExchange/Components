## <img src='./logo.jpg' width='40' height='40'>tQlikviewInput

### Overview
Reads data from QVX (QlikView data eXchange) files and pushs rows to standard flow.
It can extracts fields properties from qvx (QvxTableHeader) and creates the talend metadata xml file (ready to import into repository as generic metadata; I'm sorry but I didn't found a solution to manage a custom metadata type, I read some post, blog and so but neither works fine!).
Parameters:
date format string (used for talend metadata)
charset (typically is utf-8)
data buffer size (it's the buffer size loaded in memory; useful if document is very large)
text buffer size (it's the buffer used to store text fields when reading; insert a value larger to fit you longest text value)
debug (to print debug information).


### Images




#### Release Notes

##### 0.1 - 2014-08-07 14:57:19
This is the first beta version. I tried it with different qvx documents and works correctly. Please give me feedback if you get problems.
### Compatible
 -  5.4 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)