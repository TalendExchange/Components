# btence
  <nospam+btence.l@gmail.com>

## <a href='./components/tJasperOutputExchange/readme.md'><img src='./components/tJasperOutputExchange/logo.jpg' width='40' height='40'> tJasperOutputExchange</a>
 :warning: Compatibility not known

tJasperOutput seems coming from JasperETL. This leads to a quite long release cycle so that new versions (and new capabilities) of JasperReport could be used with Talend.
This component is based on the tJasperOutput included in Talend and JasperETL, but aims to use last version of jars and possibly add interesting options.

Before version 3.5.1-1 of this component, the component wrote a CSV file and then called Jasper's API to output a report. Since version 3.5.1-1, it uses an XML file.
As a consequence :
- in your report, the "description" of all fields should be the field name (at least Talend's flow field name)
- you can now use sub-reports (and possibly List - not tested) using (sub)dataset. The dataset should have as DataSource something like :
$P{REPORT_DATA_SOURCE} instanceof net.sf.jasperreports.engine.data.JRXmlDataSource ? ((net.sf.jasperreports.engine.data.JRXmlDataSource)$P{REPORT_DATA_SOURCE}).dataSource("/root/row") : $P{REPORT_DATA_SOURCE}
<img src='./components/tJasperOutputExchange/sample.jpg'>
