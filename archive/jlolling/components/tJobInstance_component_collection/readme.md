## <img src='./logo.jpg' width='40' height='40'>tJobInstance_component_collection

### Overview
These 4 components:
- tJobInstanceStart
- tJobInstanceEnd
- tJobDataRangeScanner
- tJobInstanceLiveCheck
are dedicated to manage job monitoring.
Helps you to have all essential information for every job run:
What has the job done, what comes in, what is the result...
Where, when, how how runs the jobs....
 
Please refer the linked documentation
The release 3.0 needs slightly changed tables!
Please contact me in case of questions and do not use the rating function to post questions.

### Details
* Creates an job instance Id to mark the datasets for data lineage
* holds all necessary information about a job run in a table
* keeps all context variables in a table (at the job start and its end)
* keeps as much as needed counters from the job
* provides incremental loads
* provides a lot of key figures about the last job run
* keeps the error messages from the job in the status table
* enables Log4J for the job with various outputs and allows using context variables whithin the logging
* Provides maximum memory usage tracking
### Images
<a href='./screenshots/v_4.1__15.jpg'><img src='./screenshots/v_4.1__15.jpg' ></a>
<a href='./screenshots/v_4.1__14.jpg'><img src='./screenshots/v_4.1__14.jpg' ></a>
<a href='./screenshots/v_4.1__13.jpg'><img src='./screenshots/v_4.1__13.jpg' ></a>
<a href='./screenshots/v_3.4__12.jpg'><img src='./screenshots/v_3.4__12.jpg' ></a>
<a href='./screenshots/v_3.4__11.jpg'><img src='./screenshots/v_3.4__11.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tJobInstance>Source Code on Github</a>
 * <a href=http://jan-lolling.de//talend/cimt_framework/talend_job_instance_components_usecases.pdf>Documentation Concept and Use Cases</a>
 * <a href=https://github.com/jlolling/talendcomp_tJobInstance/blob/master/doc/tJobInstanceStart.pdf>Documentation Components</a>

#### Release Notes

##### 3.0 - 2014-07-20 17:32:42
republished
Log4J support for jobs added 
##### 3.2 - 2014-08-19 10:19:52
Bug fixed: Job end timestamp not in the previous job info
tJobInstanceLiveCheck component added
tJobInstanceEnd can use a separate database connection to fix issues for long running jobs.
##### 3.3 - 2014-09-12 09:06:48
Problems with open database connections fixed
Memory usage tracking added. Please refer the documentation!
##### 3.4 - 2014-10-11 16:55:22
Bug fixed: If the tJobInstanceEnd component use a separate connection and logging is enabled, the writing of the named counters fails.
##### 4.1 - 2015-01-14 23:09:48
Enhancement:
The last job instance can be additional (next to the job name) selected by the work item. This allows to have one job for different purposes with the full advantage of the gathering of the last job instance gathering.
Bug fixed: In a situation where the job runs follows within 10ms the last job run takes not the last, instead a much older one.
### Compatible
 -  5.1 (obsolete)
 -   5.3 (obsolete)
 -   5.4 (obsolete)
 -   5.5 (obsolete)
 -   5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)