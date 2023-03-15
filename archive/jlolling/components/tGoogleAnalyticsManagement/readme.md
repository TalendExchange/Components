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
<a href='./screenshots/v_5.1__12.jpg'><img src='./screenshots/v_5.1__12.jpg' ></a>
<a href='./screenshots/v_5.1__11.jpg'><img src='./screenshots/v_5.1__11.jpg' ></a>
<a href='./screenshots/v_5.0__9.jpg'><img src='./screenshots/v_5.0__9.jpg' ></a>
<a href='./screenshots/v_5.0__10.jpg'><img src='./screenshots/v_5.0__10.jpg' ></a>
<a href='./screenshots/v_4.1__8.jpg'><img src='./screenshots/v_4.1__8.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tGoogleAnalyticsManagement>Source Code on Github</a>
 * <a href=http://jan-lolling.de/talend/components/help/tGoogleAnalyticsManagement.pdf>Documentation</a>
 * <a href=http://jan-lolling.de/talend/howtos/google_service_account/create-a-google-service-account.html>How to create a Google service account</a>

#### Release Notes

##### 1.5 - 2014-06-29 10:02:15
release 1.5, republished
##### 2.1 - 2014-09-28 15:06:23
Google API updated to r100-1.19.0
To accounts, web properties, profiles schema changed: column selflink added
New information provided:
Goals, Goal UrlDestination Steps, Goal Event Conditions

The schema of this component are fix therefore the component must be deleted from the job and added again to get all new schema columns. 
##### 3.1 - 2014-10-22 17:24:17
New output for meta information about dimensions and metrics.
New GA API used.
##### 4.1 - 2014-12-24 00:54:08
Authentication method Client-ID for native application supported.
Output for un-sampled reports added.
New icon
##### 5.0 - 2015-01-23 19:16:08
New feature: User permissions to accounts, web properties and views can be listed.
If the current account does not have the rights to do that, there is an option to prevent the component from dying.

Known bug: The column PERMISSION_LOCAL should be nullable and in the user permission flows are non key column defined.
Workaround: Create the necessary database table manually and set a tMap between inout and output.
##### 5.1 - 2015-01-24 12:51:33
Bug fixed: The user permission flows lacks key columns
Enhancements: The flows \\"Web Property User Permissions\\" and \\"View User Permissions\\" has additionally the columns account_id and webproperty_id.

Because of a fixed defined schema has been changed, you habe to remove the component from your job and add it again, otherwise you will experience compile errors.
### Compatible
 -  5.1 (obsolete)
 -   5.2 (obsolete)
 -   5.3 (obsolete)
 -   5.4 (obsolete)
 -   5.5 (obsolete)
 -   5.6 (obsolete)