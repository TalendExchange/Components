## <img src='./logo.jpg' width='40' height='40'>tJasperReportExec

### Overview
This component can use a local jrxml file and compiles, fills and exports the report in a Talend job without a JasperServer.

It detect the need of compiling the report as well as subreports.

It uses the JasperLibrary 6.15.0 - used in the latest Jasper Studio 7

If you need Barcodes you have to add all necessary libraries with tLoadLibrary and it will work.
Please refer to the linked documentation to get more information about the necessary libraries and how to setup them.
Unlike the build in components tJasperOutput this component can use all typical data sources:
* JDBC connection (all possible database connections from Talend are enabled)
* XML files
* CSV files
* Dummy records for reports which gets its values from other sources e.g. in sub reports.

The component supports Jasper Report Books. A very nive design template to build highly complex reports.
You can set parameters and you can use resource bundles.
Please take care building a report with the correct compatibility settings inn Jaspersoft Studio. 
Please refer to the linked documentation how to do that. 
### Details
* Use JasperStudio to design your complex report file
* Run this report here in your Talend job just like you would do it in Jaspersoft Studio
* Use resource bundles
* Set report parameters gathered in your job
* Set various export options for PDF and Excel
* Can handle reports created as books
* Can use JDBC database connections, XML files or CSV files as data source.
### Images
<a href='./screenshots/v_7.2__6.jpg'><img src='./screenshots/v_7.2__6.jpg' ></a>
<a href='./screenshots/v_7.2__5.jpg'><img src='./screenshots/v_7.2__5.jpg' ></a>
<a href='./screenshots/v_7.2__4.jpg'><img src='./screenshots/v_7.2__4.jpg' ></a>
<a href='./screenshots/v_7.0__3.jpg'><img src='./screenshots/v_7.0__3.jpg' ></a>
<a href='./screenshots/v_7.0__2.jpg'><img src='./screenshots/v_7.0__2.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tJasperReportExec>Source Code</a>
 * <a href=http://jan-lolling.de/talend/components/help/tJasperReportExec.pdf>Documentation</a>

#### Release Notes

##### 1.16 - 2015-06-03 17:54:14
* Avoids problems with wrong encoding in the case of the user having a default file encoding other than UTF-8.
##### 2.6 - 2017-09-26 22:16:07
* New JasperLibrary 6.4 used
* Die on error option added
##### 2.7 - 2017-11-02 20:48:38
* Component can check if a report contains sub report references to jrxml files (necessary to run the report on a jasper server) and replace them by references to jasper files.
* new JasperLibrary 6.4.3 used
##### 3.0 - 2017-12-20 14:58:37
* Can handle reports created as books now
* Additional option to only compile the report. This is essential for parallel report execution to prevent parallel report compilation. Before a parallel execution starts this way the report can be compiled without fill and export the data.
##### 3.1 - 2018-03-29 11:23:25
* JasperLibrary 6.5.1 used
* Compatibility to Talend 6.5.1 checked and fixed
##### 3.2 - 2018-04-16 08:25:19
* Big fixed: Compile of sub reports within books does not work if sub report within detail section
##### 4.1 - 2018-11-08 15:14:27
* Current JasperLibrary 6.7.0 used
* CSV files can be used as data source
* Studio GUI layout improved
* Parameter handling improved
##### 5.1 - 2019-03-28 21:42:04
* PDF/A conformance can be used and configured
##### 5.2 - 2019-10-29 21:15:24
* Compatible to Talend 7.2.x
* Updated JasperLibrary 6.10
##### 6.1 - 2020-11-25 17:50:32
* Improved error messages in case of resources fails to load
* Bugfix for Java 11: prevent exceptions while loading image resources
##### 7.0 - 2021-09-08 10:58:22
* Bugfix for compile JasperBook based reports - cause NullPointerException if design is not fully complete.
* Performance improvements in case of using the component in parallised job runs. It prevents the component from reading the design multiple times if the same report is called multiple times.
##### 7.2 - 2022-08-18 12:11:56
* Formula fields working now
* JasperLibrary updated to the latest version 6.20
### Compatible
 - 6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2
 - 7.3
 - 8.0