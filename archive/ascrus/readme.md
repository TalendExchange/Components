# ascrus
  <nospam+ascrus@yandex.ru>

## <a href='./components/GETL (Groovy ETL library)/readme.md'><img src='./components/GETL (Groovy ETL library)/logo.jpg' width='40' height='40'> GETL (Groovy ETL library)</a>
 :warning: Compatibility not known

<img src='./components/GETL (Groovy ETL library)/sample.jpg'>

## <a href='./components/tASCUnGZIP/readme.md'><img src='./components/tASCUnGZIP/logo.jpg' width='40' height='40'> tASCUnGZIP</a>
 :warning: Compatibility not known

Un-Archiving of the GZIP file.
<img src='./components/tASCUnGZIP/sample.jpg'>

## <a href='./components/tASCVerticaClose/readme.md'><img src='./components/tASCVerticaClose/logo.jpg' width='40' height='40'> tASCVerticaClose</a>
 :warning: Compatibility not known

Closing of the Vertica connection. It is a successor of the standard component with support of TASCVerticaConnection.

<img src='./components/tASCVerticaClose/sample.jpg'>

## <a href='./components/tASCVerticaCommit/readme.md'><img src='./components/tASCVerticaCommit/logo.jpg' width='40' height='40'> tASCVerticaCommit</a>
 :warning: Compatibility not known

Confirmation of the transaction in Vertica. It is a successor of the standard component with support of TASCVerticaConnection.

<img src='./components/tASCVerticaCommit/sample.jpg'>

## <a href='./components/tASCVerticaConnection/readme.md'><img src='./components/tASCVerticaConnection/logo.jpg' width='40' height='40'> tASCVerticaConnection</a>
 :warning: Compatibility not known

Opening connection to the Vertica version 5 or 6. It is a successor of the standard component with support of Vertica 5 and 6 drivers. Working with components tASCVertica*.

<img src='./components/tASCVerticaConnection/sample.jpg'>

## <a href='./components/tASCVerticaCreateTable/readme.md'><img src='./components/tASCVerticaCreateTable/logo.jpg' width='40' height='40'> tASCVerticaCreateTable</a>
 :warning: Compatibility not known

Creates table or temporary table based on the description of the component schema in the job. All types of fields are supported excepting Object, List and Binary, it is possible to refer to the primary key.

P.S. Connect using tASCVerticaConnect.
<img src='./components/tASCVerticaCreateTable/sample.jpg'>

## <a href='./components/tASCVerticaFileOut/readme.md'><img src='./components/tASCVerticaFileOut/logo.jpg' width='40' height='40'> tASCVerticaFileOut</a>
 :warning: Compatibility not known

Query the Vertica and save it as a CSV file. You can set the column separator, text encoding, text separator and value for NULL fields.

P.S. Connect using tASCVerticaConnect.
<img src='./components/tASCVerticaFileOut/sample.jpg'>

## <a href='./components/tASCVerticaInput/readme.md'><img src='./components/tASCVerticaInput/logo.jpg' width='40' height='40'> tASCVerticaInput</a>
 :warning: Compatibility not known

Returns the Vertica inquiry data in the flow. It is a successor of the standard component with support of Vertica 5 and 6 drivers.

P.S. Connect using tASCVerticaConnect.
<img src='./components/tASCVerticaInput/sample.jpg'>

## <a href='./components/tASCVerticaLoad/readme.md'><img src='./components/tASCVerticaLoad/logo.jpg' width='40' height='40'> tASCVerticaLoad</a>
 :warning: Compatibility not known

Uploads the data from the flow into Vertica. Allows to upload the data as well directly into the indicated table as also through the automatically created temporary buffer table. It support the operations of input, change, removal and consolidation of records as well as the input of only new records and removal of no more existing in the loaded data. The upload of the direct writing mode in ROS is supported.

Read more in readme.doc
<img src='./components/tASCVerticaLoad/sample.jpg'>

## <a href='./components/tASCVerticaOutput/readme.md'><img src='./components/tASCVerticaOutput/logo.jpg' width='40' height='40'> tASCVerticaOutput</a>
 :warning: Compatibility not known

<img src='./components/tASCVerticaOutput/sample.jpg'>

## <a href='./components/tASCVerticaProc/readme.md'><img src='./components/tASCVerticaProc/logo.jpg' width='40' height='40'> tASCVerticaProc</a>
 :warning: Compatibility not known

Executes the SQL script of Vertica.

It is allowed in the script to show a command package which are delimited by a semicolon. It does not allow to use SELECT which returns the dataset. 

Macro-variables are supported in the script, their values can be set up in the component. Macro-variables are subset as inline text without indication of types. Therefore an autonomic transformation of subset values into needed format is required.

The following macro commands are supported in the script: Set the variables, conditions, loops through the records, the echo.

More in readme.doc
<img src='./components/tASCVerticaProc/sample.jpg'>

## <a href='./components/tASCVerticaRollback/readme.md'><img src='./components/tASCVerticaRollback/logo.jpg' width='40' height='40'> tASCVerticaRollback</a>
 :warning: Compatibility not known

Rollback of the transaction in Vertica. It is a successor of the standard component with support of TASCVerticaConnection.

<img src='./components/tASCVerticaRollback/sample.jpg'>

## <a href='./components/tASCVerticaRow/readme.md'><img src='./components/tASCVerticaRow/logo.jpg' width='40' height='40'> tASCVerticaRow</a>
 :warning: Compatibility not known

Executes a request into Vertica with a possibility to return the result as a cycle. It is a successor of the standard component with support of Vertica 5 and 6 drivers.

P.S. Connect using tASCVerticaConnect.
<img src='./components/tASCVerticaRow/sample.jpg'>

## <a href='./components/tASCVerticaTableBulkLoad/readme.md'><img src='./components/tASCVerticaTableBulkLoad/logo.jpg' width='40' height='40'> tASCVerticaTableBulkLoad</a>
 :warning: Compatibility not known

Upload of the CSV file with header in the line into the Vertica table.

The component receives the table schema from the database and associates its fields with the names of the columns in the file. It is possible to manually indicate the mapping of the association for the table fields and file columns which have different names. It is not required to describe the structures of the table fields in the component which allows to dynamically upload the data having previously unknown columns. It is possible to specify the mapping of fields from the input flow.

<img src='./components/tASCVerticaTableBulkLoad/sample.jpg'>
