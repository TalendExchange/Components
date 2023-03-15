# ManfredF
  <nospam+manfred.fettinger@krausnaimer.com>

## <a href='./components/tFlowToSapRfcTable/readme.md'><img src='./components/tFlowToSapRfcTable/logo.jpg' width='40' height='40'> tFlowToSapRfcTable</a>
 :warning: Compatibility not known

Prepares a flow to pass it as a table parameter to a SAP RFC Function Module

To use this component, you have to put it after a flow output and before a SAP-Component like tSAPInput which calls an RFC-Function Module where you have to pass a table parameter. 

In the SAP-Component at "Initialize Input" insert "globalMap.get(COLUMNNAME)" 
where COLUMNNAME is the name of the current column in upper case letters!



<img src='./components/tFlowToSapRfcTable/sample.jpg'>
