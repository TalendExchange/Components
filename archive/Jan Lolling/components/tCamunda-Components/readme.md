## <img src='./logo.jpg' width='40' height='40'>tCamunda-Components

### Overview
Talend Jobs as External Task Worker:
Camunda BPMN offers the feature External Tasks. Such tasks have to solve in external programs to prevent the BPMN engine from stick with expensive resource handling.
The communication to Camunda can be build with native Talend components but this leads to a huge complex job.
Theses components simplifying the task handling and make the available as simple inputs and outputs.

The components provides the tasks simply as input flow and the response to Camunda is simply a output flow (or triggered).
The components also provides error handling and retries in case of communication problems to keep out such complexity from the job.
The external task components provides JMX MBeans providing metrics for all kind of requests and for the actual work.

Talend Job starting a Camunda process instance:
You can start right from the job a Camunda process instance and provide variables for the process and retrieve variables changed within the process.
### Details
* Simplifies the task handling drastically and enables a Talend developer to focus on the actual job
* Build-in error handling
* Start Camunda process instances based on a process definition
* Minimize http requests by enabling the new Camunda long polling feature (available since Camunda 7.1.1)
* Check the health of your external tasks over JMX interface
### Images
<a href='./screenshots/v_8.0__60.jpg'><img src='./screenshots/v_8.0__60.jpg' ></a>
<a href='./screenshots/v_8.0__59.jpg'><img src='./screenshots/v_8.0__59.jpg' ></a>
<a href='./screenshots/v_8.0__58.jpg'><img src='./screenshots/v_8.0__58.jpg' ></a>
<a href='./screenshots/v_8.0__57.jpg'><img src='./screenshots/v_8.0__57.jpg' ></a>
<a href='./screenshots/v_8.0__56.jpg'><img src='./screenshots/v_8.0__56.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tCamundaComponents>Source Code</a>
 * <a href=https://github.com/jlolling/talendcomp_tCamundaComponents/wiki>Documentation</a>

#### Release Notes

##### 1.4 - 2018-04-27 12:27:29
* Tested and productive version
* Improved http connection handling
##### 2.0 - 2018-05-18 12:56:50
* Component to start a process instance added
##### 2.1 - 2018-05-25 17:41:56
* Fetch and Lock can now take care about task priority
##### 2.2 - 2018-05-31 20:00:55
* Improvements in tCamundaPorcessInstanceStart: you setup variables only as return variables
* Bug fix: timeout was not applied for the very first request.
##### 4.1 - 2018-07-02 19:41:09
* Allows Bulk-processing of tasks
* Improved error handling
##### 4.2 - 2018-07-06 18:48:03
* tCamundaExtTaskComplete can deal with completes without variables. In Talend a flow without variable is not possible, now you can decide to use this variable or not.
* Negative values for retries will be suppressed (set to 0). This simplifies the retries handling.
* Update the Jackson JSON library
##### 6.0 - 2018-09-15 08:32:39
* Bulk mode implemented
* tCamundaUpdateProcessVariables added
##### 6.4 - 2018-11-05 20:23:03
* Security issues solve. Updated jackson-bind library updated to 2.9.5
* Performance improvements because authetication is now preemptive
##### 7.3 - 2019-08-12 20:43:51
* JMX support added: Various metrics now available over JMX MBeans to check the health of your external tasks and an operation to tear down the task gracefully
* Bug fix for check task exiration: Milliseconds was ignored
##### 8.0 - 2019-10-28 20:28:06
* Compatible with Talend 7.2.x now
* Camunda Long polling feature implemented (asnchron response timeout)
### Compatible
 -  6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)
 -   6.4 (obsolete)
 -  6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2