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
<a href='./screenshots/v_13.5__99.jpg'><img src='./screenshots/v_13.5__99.jpg' ></a>
<a href='./screenshots/v_13.5__98.jpg'><img src='./screenshots/v_13.5__98.jpg' ></a>
<a href='./screenshots/v_13.5__97.jpg'><img src='./screenshots/v_13.5__97.jpg' ></a>
<a href='./screenshots/v_13.5__96.jpg'><img src='./screenshots/v_13.5__96.jpg' ></a>
<a href='./screenshots/v_13.5__95.jpg'><img src='./screenshots/v_13.5__95.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tFileExcel/blob/master/doc/tFileExcelSheetOutput.pdf>Documentation tFileExcelSheetOutput</a>
 * <a href=https://github.com/jlolling/talendcomp_tFileExcel>Source Code on Github</a>
 * <a href=https://github.com/jlolling/talendcomp_tFileExcel/blob/master/doc/tFileExcelSheetInput.pdf>Documentation tFileExcelSheetInput</a>

#### Release Notes

##### 6.8 - 2015-04-06 14:36:56
Uses the latest Apache POI API release 3.12 beta1
Allow rendering numbers without thousand separator
##### 6.9 - 2015-04-19 15:32:27
* Clearyfies the meaning of the memory saving mode as dedicated for writing large files
* Allows to read files in this mode (but not with the advantage of memory saving, this is under development)
##### 8.9 - 2017-11-15 14:01:19
* Date parsing improved: In case of a previous column has a pattern different the current column, this can lead to problems with the automatic date pattern detection.
* new Apache-POI API used
* bug fix for the misplacement of the comments
##### 10.0 - 2018-03-14 21:50:55
* TEXT cell format for cells written with plain text (except formulas and the header line)
* Shift row function added
##### 10.2 - 2018-04-20 21:18:53
* Bug fix for damaged data format setting
##### 10.3 - 2018-11-12 10:45:05
* Bug solved: The release 10.1 has introduced a bug which prevents the component from applying the data format when a header line was written before.
* The name of the target sheet can be set as integer index. If a sheet with this index exists, it will be used, otherwise a new sheet with the name "Sheet" will be created.
* The current version of the Apache-POI API: 3.17
* Label of the option "Remove last empty rows" changed to "Remove the rows below the last written row" because this is the actual behaviour
* Take care writing into named cells never change the cell style
##### 11.0 - 2018-11-27 22:11:18
* tFileExcelReferencedCellOutput has no an advanced option to not set cell style. This helps if you write into existing formatted cells
* tFileExcelSheetInput has an option to close the workbook. This improves the resource handling in case of a job only reads from excel.
* The component tFileExcelSheetOutput allows now in the mode "Append rows" to apply the style of the previous existing cells to the new appended cells.
* An old bug is fixed: The data format setting was not correctly applied when the first column is not A.
##### 11.1 - 2019-09-25 09:51:19
* Latest Apache-POI API 4.1.0 used. This make these components compatible with Talend Studio 7.2.1
##### 11.2 - 2019-10-08 09:13:51
* Bug fixed: tFileExcelSheetInput returns the formula itself instead of the value if the value is type of text.
* French translation of the component setting labels are greatly improved and updated by Christian Blaise - thanks a lot for the kind support!
##### 11.3 - 2019-10-27 22:06:02
* compatible to Talend Studio 7.2.x
##### 11.5 - 2019-12-15 18:26:43
* tFileExcelSheetOutput improved: appending data now can extend conditional styles and tables and use the style from the previous row
* Bug fixed: Compatibility with Karaf container fixed
##### 12.0 - 2020-03-23 07:34:35
* tFileExcelSheetOutput: improvd append mode. The start row now works in append mode as pointer to the row from which the styles will be taken.
* additional components added: tFileArchive2 and tFileUnArchive2 are clones of the original build-in components but with updated libs to prevent incompatibility with the Excel components
* Apache POI API: updated version used
##### 12.1 - 2020-03-30 22:37:32
* Improved Append mode: can now also be used if there are no previous records are written.
* Log4J shipped to prevent problems with Talend 7.3.1 (in this version of Talend log4j is not part or the distribution anymore)
##### 12.4 - 2020-10-15 15:29:49
* Append rows mode works now reliable.
* While appending rows, the styles to copy will be taken from the initially used first written row (the start row setting)
* Log4J dependency removed, so it is not necessary anymore to change the whole project to log4j v1
##### 12.5 - 2021-01-11 20:29:35
* Bug solved: https://github.com/jlolling/talendcomp_tFileExcel/issues/26 : tFileExcelSheetOutput damages styles for text cells if there is no style handling option choosen and the cells are preformatted.
##### 13.1 - 2021-06-29 11:32:22
* New component tFileExcelSheetInputUnpivot add - please refer to the documentation of tFilöeExcelSheetInput
* tFileExcelSheetInput: tolerant search for sheet name to read. Optionally you can ignore case sensitivity, spaces and underscores with the new option.
* tFileExcelSheetInput: bug solved: error message if sheet was not found was wrong
* tFileExcelSheetOutput: Bug solved: data formats set in the component column config was partially ignored.
##### 13.2 - 2021-07-30 09:40:31
* tFileExcelSheetInput: bug solved: In case the cell contains a broken formula and the actual cell type is NUMERIC and the job wants to have the value as String - in this case the component returned the formula instead of the cached numeric value.
* tFileExcelList: Return value label fixed
##### 13.3 - 2021-10-04 18:03:23
* Feature: Schema columns typed as Object allow now also to set format patterns (Thanks to Sven from cimt objects AG for notifying me about that issue)
##### 13.4 - 2021-12-17 21:37:41
* tFileExcelReferencedCellOutput bug fixes: Cell address was not correct calculated if cell-reference was given. Error handling improved.
##### 13.5 - 2022-05-23 08:04:53
* Bug solved: When configuring the columns based on a header row and this row does not exist: this has caused a NullPointerException and not a meaningful error message. Now the component throws an exception with sheet name and the expected header row index to support file investigation.
### Compatible
 - 7.0 (retired)
 -  7.1 (retired)
 - 7.2
 - 7.3
 - 8.0