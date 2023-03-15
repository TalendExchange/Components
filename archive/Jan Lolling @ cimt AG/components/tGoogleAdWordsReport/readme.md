## <img src='./logo.jpg' width='40' height='40'>tGoogleAdWordsReport

### Overview
This component handles Googles AdWords-API with the latest release v201809.
It authorise the user, executes the report and download the result as text file.
The query can be setup with the AdWords-Query-Language or with given report-type and fields.
To use this component please take care you understand the basics of the AdWordsReports. Refer to the Google description (linked here).
You need:
1. A developer token. You have to order this by Google
2. AdWords account
3. Client-Customer-ID
4. Technical credentials (Service Account or Client-ID for native applications)
The setup procedure in AdWords is not an easy task.
The component can download the report results in the formats CSV or XML. This formats can easily read by the Talend build-in components.
For CSV files the fields are exactly in the order or the AWQL or the give fields in the component.
The result can also send as flow into the job.
### Details
* Latest Google AdWords reporting API (v201809)
* Easy to handle and to manage.
* Brings the report data into you own data ware house.
* Download result as file or provide it as flow
* Use AdWord Query Language or define the report per parameters
### Images
<a href='./screenshots/v_7.0__2.jpg'><img src='./screenshots/v_7.0__2.jpg' ></a>
<a href='./screenshots/v_7.0__1.jpg'><img src='./screenshots/v_7.0__1.jpg' ></a>


### Resources
 * <a href=http://jan-lolling.de/talend/components/help/tGoogleAdWordsReport.pdf>Documentation</a>
 * <a href=https://github.com/jlolling/talendcomp_tGoogleAdwordsReports>Source Code on Github</a>

#### Release Notes

##### 7.0 - 2017-03-07 19:38:16
* NEW: Google AdWords API v201702 used
* Updated build process
### Compatible
 -  5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)