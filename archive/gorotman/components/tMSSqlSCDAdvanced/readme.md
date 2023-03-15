## <img src='./logo.jpg' width='40' height='40'>tMSSqlSCDAdvanced

### Overview
This component manage a slowly changing dimension table in a data warehouse environment, starting from the source table and its rows changing.


![screenshot](https://talendforge.org/exchange/tos/upload_tos/extension-1193/screenshot.jpg)
### Details
- operation (insert,update) choosed by changes on columns
- manage audit columns
- versioning based columns: start/end date, counter, last version flag
- history correction option
- various options for versioning start/end date (job start time, current day, current month, calculated in the job)
- specific options for 1st version rows
- search in memory (preload current rows) vs query row-by-row
### Images



### Install Instructions
Standard procedure.

#### Release Notes

##### 0.1 - 2014-05-08 08:36:30
With new portal, previous releases are missing and I don't know which one has been migrated here. So this is 0.4 release and these are release notes for all previous:
Rel 0.2:
• Execution without versioning: component can run without versioning column. Before this release, the component causes errors if versioning options (start
date, end date, and so) still empty.
• Value for missing rows: Before this release, the component cause wrong code if there are columns with audit option but without value for missing rows.
The option to close missing target rows could be checked or not, problem occurs either. Now an audit column without value for missing rows, will be
translated to an empty string (for string) and to null (for others types), in missing target rows.
Rel 0.3:
• Resolved some bugs (timestamp for versioning date and others)
Rel 0.4:
• Static class used for type remapping (talend->java), changed from HashMap to TreeMap with insensitive search option (CASE_INSENSITIVE_ORDER);
duplicated keys are removed; remaining keys are low-case only. Changed class: “javaTypeToResultSetGetter”, “javaTypeToSqlStatemetSetter”,
“javaTypeToJavaSqlType” located in class Utility and CLASS (a copy of talend skeleton).
• Added code for “java.math.BigDecimal”
• Versioning Rule: “given” option now gets value from source flow column (before it accepts a fixed value or a variable). Please refer to guide for details. If
you used this option in previous version, you have to manually change your job (sorry me but now is more useful) adding a column in a tMap and use this
to store your fixed value.
### Compatible
 -  5.5 (obsolete)
 -   5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)