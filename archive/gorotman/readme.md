# gorotman
  <nospam+simone.fresch@ftcoop.it>

## <a href='./components/tAccessColumnList/readme.md'><img src='./components/tAccessColumnList/logo.jpg' width='40' height='40'> tAccessColumnList</a>
 :warning: Compatibility not known

An implementation of column listing for Microsoft Access (.mdb).
I copied a generic columnList existing component and added specific code.
So thank's to original developer......
<img src='./components/tAccessColumnList/sample.jpg'>

## <a href='./components/tAccessTableList/readme.md'><img src='./components/tAccessTableList/logo.jpg' width='40' height='40'> tAccessTableList</a>
 :warning: Compatibility not known

An implementation of tables listing for Microsoft Access (.mdb).
I copied a generic tableList existing component and added specific code.
So thank\\'s to original developer......
<img src='./components/tAccessTableList/sample.jpg'>

## <a href='./components/tFolderCreate/readme.md'><img src='./components/tFolderCreate/logo.jpg' width='40' height='40'> tFolderCreate</a>
 :warning: Compatibility not known

This component create an empty folder in the given path. There are two options: if exists, before delete it (empty or not empty!); if parent(s) does not exist(s), create the full path. There is also the standard "fails on error" option.
<img src='./components/tFolderCreate/sample.jpg'>

## <a href='./components/tMSSqlSCDAdvanced/readme.md'><img src='./components/tMSSqlSCDAdvanced/logo.jpg' width='40' height='40'> tMSSqlSCDAdvanced</a>
 :warning: Compatibility not known

This component manage a slowly changing dimension table in a data warehouse environment, starting from the source table and its rows changing.



<img src='./components/tMSSqlSCDAdvanced/sample.jpg'>

## <a href='./components/tQlikviewInput/readme.md'><img src='./components/tQlikviewInput/logo.jpg' width='40' height='40'> tQlikviewInput</a>
 :warning: Compatibility not known

Reads data from QVX (QlikView data eXchange) files and pushs rows to standard flow.
It can extracts fields properties from qvx (QvxTableHeader) and creates the talend metadata xml file (ready to import into repository as generic metadata; I'm sorry but I didn't found a solution to manage a custom metadata type, I read some post, blog and so but neither works fine!).
Parameters:
date format string (used for talend metadata)
charset (typically is utf-8)
data buffer size (it's the buffer size loaded in memory; useful if document is very large)
text buffer size (it's the buffer used to store text fields when reading; insert a value larger to fit you longest text value)
debug (to print debug information).


<img src='./components/tQlikviewInput/sample.jpg'>
