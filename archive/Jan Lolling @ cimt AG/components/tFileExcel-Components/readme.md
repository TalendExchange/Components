## <img src='./logo.jpg' width='40' height='40'>tFileExcel-Components

### Overview
The component suit constists of:
tFileExcelWorkbookOpen - Opens a workbook by reading a file or simply create an empty new one
    * detect automatically the file type - no need to declare it as setting
    * encrypt password secured files
tFileExcelWorkbookSave
    * write a workbook 
    * recalculate all formulas
    * encrypt the file with a password
    * automatically set the necessary file extension
tFileExcelSheetInput - read an Excel sheet with lots of comfort functions
    * Automatic adjustment of the columns to read
    * Read comments
    * Read cell style
    * Read and interpret date formats very tolerant
    * Read only the columns you need
    * Can skip erroneous cell content
tFileExcelSheetInputUnpivot
    * unpivots (or normalize) values from columns which are dynamically and not static
tFileExcelSheetOutput - write Excel sheets
    * write vertically (optional)
    * write only the columns you need
    * recalculate tables if they are affected (and update this way pivot tables)
    * recalculate conditional cell styles
    * apply cell styles from the first (or two) rows
    * apply cell data validation
    * write formulas
    * apply data validation to the new row (taken from the first written row)
    * shift existing row before writing the new row
tFileExcelSheetList
    * List all sheets
    * provide meta information about the sheets
tFileExcelNamedCellInput
    * read named cells
tFileExcelNamedCellOutput
    * write named cells
tFileExcelReferencedCellInput
    * read cells be absolut references
tFileExcelReferencedCellOutput
    * write into absolut referenced cells





### Details
* Read and write excel files with the Apache-POI API
* Fit to the need of Excel-"fighter" which have to deal with real-live Excel tasks
* Build stunning Excel files
* Read with most possible flexibility (including now unpivot data)
### Images
<a href='./screenshots/v_8.6__9.jpg'><img src='./screenshots/v_8.6__9.jpg' ></a>
<a href='./screenshots/v_8.6__8.jpg'><img src='./screenshots/v_8.6__8.jpg' ></a>
<a href='./screenshots/v_8.6__18.jpg'><img src='./screenshots/v_8.6__18.jpg' ></a>
<a href='./screenshots/v_8.6__17.jpg'><img src='./screenshots/v_8.6__17.jpg' ></a>
<a href='./screenshots/v_8.6__16.jpg'><img src='./screenshots/v_8.6__16.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tFileExcel/blob/master/doc/tFileExcelSheetOutput.pdf>Documentation tFileExcelSheetOutput</a>
 * <a href=https://github.com/jlolling/talendcomp_tFileExcel>Source Code on Github</a>
 * <a href=https://github.com/jlolling/talendcomp_tFileExcel/blob/master/doc/tFileExcelSheetInput.pdf>Documentation tFileExcelSheetInput</a>

#### Release Notes

##### 6.11 - 2015-10-22 21:29:38
* Supports the output file encryption
* Uses the new Apache POI release 3.13
##### 6.12 - 2016-01-19 22:02:13
* Bug fixed: Menomry saving mode does not work correctly 
* Prepared to allow shifting rows in tFileExcelSheetOutput (release 6.9)
* Solves the problem: the template input file is kept reading and cannot moved or deleted
##### 6.13 - 2016-02-07 21:02:47
* Fixes a bug in the processing of conditional formats. Now the formats can span multiple columns and the number of rules per conditional format can exceed 3 rules.
* Solves the problem the input file cannot be moved or deleted within the same job.
##### 7.0 - 2016-03-17 10:53:21
* Feature added: Data validation can be reused. Use this option in the component tFileExcelSheetOutput
##### 7.1 - 2016-05-22 15:47:19
* Is now compatible with the XML parsers in the Talend Runtime (Talend Runtime must run with a Java 8 JDK !)
* Missing input file will throw a meaningful error message (not the "zip file is closed" message anymore)
##### 7.2 - 2016-07-22 17:40:27
* Bug fixed: Conditional formats causes an exception if the number of rules exact 3
##### 8.3 - 2017-01-26 22:10:37
* This component must be updated first
* Supports automatically date and time parsing
* Bug solved: double values returned as String are now not limited to 3 digits precision
* new stable POI API release 3.15 used
##### 8.6 - 2017-03-13 20:49:43
* Combined release of all Excel components in a constinent and reliable way
* tFileExcelSheetInput can optionally exclude strange date values like 0000-00-00
### Compatible
 -  5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)