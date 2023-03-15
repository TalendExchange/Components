## <img src='./logo.jpg' width='40' height='40'>tJasperReportExec

### Overview
This component can use a local jrxml file and compiles, fills and exports the report in a Talend job without a JasperServer.
It detect the need of compiling the report as well as subreports.
It uses the JasperLibrary 6.1.1
If you need Barcodes you have to add all necessary libraries with tLoadLibrary and it will work.
Please refer to the linked documentation to get more information about the necessary libraries and how to setup them.
Unlike the build in components tJasperOutput this component can use all typical data sources:
JDBC connection (all possible database connections from Talend are enabled)
You can set parameters and you can use resource bundles.
XML files
Dummy records for reports which gets its values from other sources e.g. in sub reports.
Please take care building a report with the correct compatibility settings inn Jaspersoft Studio. Please refer to the linked documentation how to do that. 
### Details
* Use JasperStudio to design your complex report file
* Run this report here in your Talend job just like you would do it in Jaspersoft Studio
* Use database connection or XML files as data sources
* Use resource bundles
* Set report parameters gathered in your job
* Set various export options for PDF and Excel
### Images
<a href='./screenshots/v_1.11__1.jpg'><img src='./screenshots/v_1.11__1.jpg' ></a>


### Resources
 * <a href=http://jan-lolling.de/talend/components/help/tJasperReportExec.pdf>Documentation</a>
 * <a href=https://github.com/jlolling/talendcomp_tJasperReportExec>Source Code on Github</a>

#### Release Notes

##### 1.11 - 2014-06-29 11:12:02
republished
### Compatible
 -  5.1 (obsolete)
 -   5.4 (obsolete)
 -   5.5 (obsolete)
 -   5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)