## <img src='./logo.jpg' width='40' height='40'>tJasperOutputExchange

### Overview
tJasperOutput seems coming from JasperETL. This leads to a quite long release cycle so that new versions (and new capabilities) of JasperReport could be used with Talend.
This component is based on the tJasperOutput included in Talend and JasperETL, but aims to use last version of jars and possibly add interesting options.

Before version 3.5.1-1 of this component, the component wrote a CSV file and then called Jasper's API to output a report. Since version 3.5.1-1, it uses an XML file.
As a consequence :
- in your report, the "description" of all fields should be the field name (at least Talend's flow field name)
- you can now use sub-reports (and possibly List - not tested) using (sub)dataset. The dataset should have as DataSource something like :
$P{REPORT_DATA_SOURCE} instanceof net.sf.jasperreports.engine.data.JRXmlDataSource ? ((net.sf.jasperreports.engine.data.JRXmlDataSource)$P{REPORT_DATA_SOURCE}).dataSource("/root/row") : $P{REPORT_DATA_SOURCE}
### Images




#### Release Notes

##### 3.5.1 - 2009-05-15 10:59:43
This version uses jasperreports-3.5.1.jar instead of jasperreports-3.1.4.jar.
This implies that Jasper's "List" component can now be used directly with Talend.

A new option has been added : it allows to use Jasper's FILE_RESOLVER parameter. I wasn't able to use it properly so any help would be welcome.

Last but not least, a bug has been (partially) solved for floating point numbers. When using a local that has a different decimal separator (e.g. french) than '.', the resulting values in the report where truncated to integer values.
##### 3.5.1-1 - 2009-05-20 09:24:08
Before this version, the component wrote a CSV file and then called Jasper's  API to output a report. It now uses an XML file.
As a consequence :
- in your report, the "description" of all fields should be the field name (at least Talend's flow field name)
- but using XML is conceptually a lot better than CSV
- you can now use sub-reports (and possibly List - not tested) using (sub)dataset. The dataset should have as DataSource something like :
$P{REPORT_DATA_SOURCE} instanceof net.sf.jasperreports.engine.data.JRXmlDataSource ? ((net.sf.jasperreports.engine.data.JRXmlDataSource)$P{REPORT_DATA_SOURCE}).dataSource("/root/row") : $P{REPORT_DATA_SOURCE}

You have now an option to choose the locale used to output the report.
##### 3.5.1-2 - 2009-05-26 07:25:01
Small bug solved about xalan.jar.
This was a small bug but the component was unusable ;)
##### 3.5.2 - 2009-06-12 08:35:04
Use of JasperReports 3.5.2
##### 3.6.0 - 2009-09-01 10:06:58
Use of JasperReports 3.6.0
Temporary XML file  is now encoded in UTF8 instead of ISO-8859-15
##### 3.6.1 - 2009-11-02 16:13:50
Use of jasperreports 3.6.1
##### 3.7.0 - 2010-01-20 13:50:05
Use of jasperreports 3.7.0
### Compatible
 -  3.1 (obsolete)
 -   3.2 (obsolete)