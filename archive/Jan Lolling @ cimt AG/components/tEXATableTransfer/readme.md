## <img src='./logo.jpg' width='40' height='40'>tEXATableTransfer

### Overview
This component is dedicated to transfer the table content from one database to an EXASolution database.
The component can truncate the target table before.
This component does not care about schema differences. 
All columns existing in source and target table will be transferred, all other ignored. The necessary schema will be created internally, therefore you have to provide only the source and target table name, thats it.
The component uses asynchronous transfer to half the duration because reading and writing can take place at the same time (or overlapping).

The component can also be used to export the data as CSV files dedicated to the bulk import.

You can configure columns as to be excluded from the transfer and as well
you can add aditional columns to the output.

The component can measure for a column the min/max values and return them as return values of this component. This helps to use it in a incremental load scenario.
### Details
* Fast transfer of the data - even from different database types than EXASolution
* Export data in parallel to a bulk input file
* Detects and matches columns to be transferred automatically
* Detect automatically fields which are actually SQL keywords and enclose them automatically.
* Can measure min/max values of configured column to allow incremental load scenarios
### Images
<a href='./screenshots/v_5.4__1.jpg'><img src='./screenshots/v_5.4__1.jpg' ></a>


### Resources
 * <a href=http://jan-lolling.de/talend/components/help/tPostgresqlTableTransfer.pdf>Documentation (works pretty much like the PostgreSQL edition)</a>
 * <a href=https://github.com/jlolling/talendcomp_tDBTableTransfer>Source Code</a>

#### Release Notes

##### 5.4 - 2016-11-26 20:37:35
* new updated metadata API
* can handle table and column names wich are actually SQL keywords
* can measure min/max values
* File export use the format which expects the IMPORT command per default
### Compatible
 -  5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)
 -   6.4 (obsolete)
 -  6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)