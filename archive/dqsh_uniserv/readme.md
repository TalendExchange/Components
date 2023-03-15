# dqsh_uniserv
  <nospam+dqsh-developer-team@uniserv.com>

## <a href='./components/tUniservBTCleanse/readme.md'><img src='./components/tUniservBTCleanse/logo.jpg' width='40' height='40'> tUniservBTCleanse</a>
 :warning: Compatibility not known

tUniservBTCleanse allows Talend jobs to use the Uniserv Data Quality Batch Suite. 

Data Quality Batch Suite is a comprehensive tool to configure and run any kind of batch processing of customer data including functions for deduplication, address normalization, enrichment and more. All functions are optimized for high-speed batch processing. 

To be able to use the tUniservBTCleanse component, the Uniserv DQ Batch Suite software must be installed.

The component has its own GUI and requires an additional plugin. Please contact Uniserv for download information.

For more information on Data Quality Batch Suite, visit http://www.uniserv.com/en/products/data-quality-service-hub/data-cleansing.

<img src='./components/tUniservBTCleanse/sample.jpg'>

## <a href='./components/tUniservCDHInput/readme.md'><img src='./components/tUniservCDHInput/logo.jpg' width='40' height='40'> tUniservCDHInput</a>
 :warning: Compatibility not known

<img src='./components/tUniservCDHInput/sample.jpg'>

## <a href='./components/tUniservCDHOutput/readme.md'><img src='./components/tUniservCDHOutput/logo.jpg' width='40' height='40'> tUniservCDHOutput</a>
 :warning: Compatibility not known

<img src='./components/tUniservCDHOutput/sample.jpg'>

## <a href='./components/tUniservCDHOutputBulk/readme.md'><img src='./components/tUniservCDHOutputBulk/logo.jpg' width='40' height='40'> tUniservCDHOutputBulk</a>
 :warning: Compatibility not known

<img src='./components/tUniservCDHOutputBulk/sample.jpg'>

## <a href='./components/tUniservCDHResynchronise/readme.md'><img src='./components/tUniservCDHResynchronise/logo.jpg' width='40' height='40'> tUniservCDHResynchronise</a>
 :warning: Compatibility not known

<img src='./components/tUniservCDHResynchronise/sample.jpg'>

## <a href='./components/tUniservRTConvertName/readme.md'><img src='./components/tUniservRTConvertName/logo.jpg' width='40' height='40'> tUniservRTConvertName</a>
 :warning: Compatibility not known

tUniservRTConvertName makes the functionality of the Uniserv convert-name product available in Talend jobs. 

convert-name analyzes the name line in consumer addresses and returns its components (e.g. last name, first name, title, name prefixes, name suffixes, ...) and derives a gender key. Names that refer rather to a company or an institution are recognized as such and the legal form is analyzed if applicable.

To be able to run jobs containing the tUniservRTConvertName component, the Uniserv convert-name software must be installed.

<img src='./components/tUniservRTConvertName/sample.jpg'>

## <a href='./components/tUniservRTIdentityBulk/readme.md'><img src='./components/tUniservRTIdentityBulk/logo.jpg' width='40' height='40'> tUniservRTIdentityBulk</a>
 :warning: Compatibility not known

tUniservRTIdentityBulk allows Talend jobs to build a search index over a database of customer data for later use by tUniservRTIdentitySearch to efficiently and effectively retrieve addresses and identify duplicates even with misspelled or incomplete data.

Prepares the index pool for the search for duplicates.

To be able to use the tUniservRTIdentityBulk component, the Uniserv DQ identity RT software must be installed. 

For more information on DQ identity RT, visit http://www.uniserv.com/en/products/uniserv-data-quality-functions/identity-resolution.

<img src='./components/tUniservRTIdentityBulk/sample.jpg'>

## <a href='./components/tUniservRTIdentityOutput/readme.md'><img src='./components/tUniservRTIdentityOutput/logo.jpg' width='40' height='40'> tUniservRTIdentityOutput</a>
 :warning: Compatibility not known

tUniservRTIdentityOutput allows Talend jobs to update an existing DQ identity RT search index that has previously been built using tUniservRTIdentityBulk by inserting data for new customers, deleting existing customer entries or modifying the attributes for existing customers. 

Updates the index pool which is used for duplicate search.

To be able to use the tUniservRTIdentityOutput component, the Uniserv DQ identity RT software must be installed.

For more information on DQ identity RT, visit http://www.uniserv.com/en/products/uniserv-data-quality-functions/identity-resolution.

<img src='./components/tUniservRTIdentityOutput/sample.jpg'>

## <a href='./components/tUniservRTIdentitySearch/readme.md'><img src='./components/tUniservRTIdentitySearch/logo.jpg' width='40' height='40'> tUniservRTIdentitySearch</a>
 :warning: Compatibility not known

tUniservRTIdentitySearch allows Talend jobs to search in a DQ identity RT search index for customer data records taking into account misspellings, phonetic similarities, synonyms or missing data. 

To be able to use tUniservRTIdentitySearch, the search index has to be built using the tUniservRTIdentityBulk component.

To be able to use the tUniservRTIdentitySearch component, the Uniserv DQ identity RT software must be installed.

For more information on DQ identity RT, visit http://www.uniserv.com/en/products/uniserv-data-quality-functions/identity-resolution.
<img src='./components/tUniservRTIdentitySearch/sample.jpg'>

## <a href='./components/tUniservRTPost/readme.md'><img src='./components/tUniservRTPost/logo.jpg' width='40' height='40'> tUniservRTPost</a>
 :warning: Compatibility not known

tUniservRTPost allows Talend jobs to use the Uniserv post product for validation, correction and normalization of international addresses. 

The tUniservRTPost component may either be used with the Uniserv post software and the reference tables for the respective countries installed on site or with the Uniserv SaaS offering. 

For more information on Uniserv post, visit http://www.uniserv.com/en/products/uniserv-data-quality-functions/address-check. If you are interested in the Uniserv SaaS offering, go to http://www.data-quality-on-demand.com.

<img src='./components/tUniservRTPost/sample.jpg'>
