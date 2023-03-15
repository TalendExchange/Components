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
<a href='./screenshots/v_8.8__12.jpg'><img src='./screenshots/v_8.8__12.jpg' ></a>
<a href='./screenshots/v_8.8__11.jpg'><img src='./screenshots/v_8.8__11.jpg' ></a>
<a href='./screenshots/v_8.7__9.jpg'><img src='./screenshots/v_8.7__9.jpg' ></a>
<a href='./screenshots/v_8.7__10.jpg'><img src='./screenshots/v_8.7__10.jpg' ></a>
<a href='./screenshots/v_8.6__8.jpg'><img src='./screenshots/v_8.6__8.jpg' ></a>


### Resources
 * <a href=http://jan-lolling.de/talend/components/help/tGoogleAdWordsReport.pdf>Documentation</a>
 * <a href=https://github.com/jlolling/talendcomp_tGoogleAdwordsReports>Source Code on Github</a>

#### Release Notes

##### 7.1 - 2017-06-03 21:46:34
* Use the latest Google AdWords API 201705
##### 8.0 - 2018-03-09 11:14:21
* Use the latest Google AdWords API v201802
* Updated Google APIs for OAuth2 and http
##### 8.1 - 2018-03-22 19:24:09
* In the advanced settings the input for report download timeout added
##### 8.2 - 2019-01-31 12:47:40
* Supports the API version 2018-09
##### 8.3 - 2019-02-05 12:56:24
* Improved error message if report type is not supported
##### 8.5 - 2019-03-19 20:09:43
* Job code compile error fixed when download dir is not set and option download as file is not active
* Google APIs updated
##### 8.6 - 2019-03-27 14:12:31
* Option: include zero impressions added
##### 8.7 - 2019-09-25 12:42:28
* Compatibility to AWS solved.
##### 8.8 - 2019-10-27 22:27:17
* Compatible to Talend 7.2.x
### Compatible
 -  6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)
 -   6.4 (obsolete)
 -  6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2
 - 7.3