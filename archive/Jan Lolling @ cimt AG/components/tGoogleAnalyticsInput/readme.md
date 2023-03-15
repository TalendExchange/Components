## <img src='./logo.jpg' width='40' height='40'>tGoogleAnalyticsInput

### Overview
This component uses the Google's Core Report API (latest release 4).
You can use different ways to authorize the access:
    * Service Accounts for the enterprise users
    * Client-ID for native application for the semiprofessional usage
    * Can use the current v3 configuratio with v4 of the Analytics API without any changes. Necessary changes to the requests (e.g. the dimension ga:segment) will be added automatically internally. 
The component supports a normalised output to allow persisting the report data in a stable data model without always creating new tables for every new report.
In case of errors (which frequently occurse caused by heavy load on Google's servers) the component tries per default 5 times with an increasing wait time.

It is a good start to check the required query with the API explorer from Google: https://developers.google.com/apis-explorer/#p/

IMPORTANT:
Google has recently introduced a complete new system for Analytics called Google Analytics 4 (GA4). The current system supported by this component is now called Universal Analytics (UA).
### Details
* It is free and Open Source.
* Reports can be configured with all possible dimensions, metrics, filters, segments and sorts
* Uses always the latest Google API
* Reduce sampling with the precision settings
* Returns information about the sampling space and size in case of sampling takes places
* Provides normalised outputs -> allows to persists the data from different reports with different structures creating new tables or change the structure of database tables
* Bullet proof error handling: in case of errors the component waits a bit an retry the requests (configurable)
* Compatible with v4 of the new Analytics API.
* All features of v4 usable by defining the report in the Google API explorer and copy past the json report description in the component.
### Images
<a href='./screenshots/v_8.3__4.jpg'><img src='./screenshots/v_8.3__4.jpg' ></a>
<a href='./screenshots/v_8.3__3.jpg'><img src='./screenshots/v_8.3__3.jpg' ></a>
<a href='./screenshots/v_8.3__2.jpg'><img src='./screenshots/v_8.3__2.jpg' ></a>
<a href='./screenshots/v_8.3__1.jpg'><img src='./screenshots/v_8.3__1.jpg' ></a>


### Resources
 * <a href=http://jan-lolling.de/talend/howtos/google_service_account/create-a-google-service-account.html>How to create a Google service account</a>
 * <a href=http://jan-lolling.de/talend/components/help/tGoogleAnalyticsInput.pdf>Documentation</a>
 * <a href=https://github.com/jlolling/talendcomp_tGoogleAnalyticsInput>Source Code on Github</a>

#### Release Notes

##### 8.3 - 2017-01-28 09:37:51
* New Google API used
### Compatible
 -  5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)