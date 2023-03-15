## <img src='./logo.jpg' width='40' height='40'>tGoogleAnalyticsManagement

### Overview
This component uses the Management API to collect all available items for your account like web property, profiles, segments and goals (also with URL destination steps and event conditions).
NEW: provides an output flow with describing information about all available dimensions and metrics (all columns).

NEW: Provides output flows for the user permissions to accounts, web properties and views.
The schemas has been changed (some additional columns added). 
Therefore please remove the component from your job and add it again. Unfortunately I do not know any other way to force the Studio to accept a new fixed defined schema.
### Details
Collect everything whats necessary to have an great overview over the Google Analytics Accounts and all other metadata:
* Accounts
* Web Properties
* Views
* Goals
* Segments
* Dimension and Metrics descriptions
* User Permissions
* Custom Data Sources
* Unsampled Reports
* AdWords account links
* Improved error handling (retries failed attempts multiple times - when it make sense).
### Images
<a href='./screenshots/v_7.0__4.jpg'><img src='./screenshots/v_7.0__4.jpg' ></a>
<a href='./screenshots/v_7.0__3.jpg'><img src='./screenshots/v_7.0__3.jpg' ></a>
<a href='./screenshots/v_6.3__2.jpg'><img src='./screenshots/v_6.3__2.jpg' ></a>
<a href='./screenshots/v_6.3__1.jpg'><img src='./screenshots/v_6.3__1.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tGoogleAnalyticsManagement>Source Code on Github</a>
 * <a href=http://jan-lolling.de/talend/components/help/tGoogleAnalyticsManagement.pdf>Documentation</a>
 * <a href=http://jan-lolling.de/talend/howtos/google_service_account/create-a-google-service-account.html>How to create a Google service account</a>

#### Release Notes

##### 6.3 - 2015-12-18 17:44:15
* updated Google APIs
##### 7.0 - 2016-04-24 13:05:58
* Output flow Dimension & Metrics provides additional information about since when the dimension or metric was added (especcially important if you decide to switch to Analytocs API v4)
* updated Google library
### Compatible
 -  5.4 (obsolete)
 -   5.5 (obsolete)
 -   5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)
 -   6.4 (obsolete)
 -  6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)