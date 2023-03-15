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
<a href='./screenshots/v_5.0__3.jpg'><img src='./screenshots/v_5.0__3.jpg' ></a>
<a href='./screenshots/v_5.0__2.jpg'><img src='./screenshots/v_5.0__2.jpg' ></a>
<a href='./screenshots/v_5.0__1.jpg'><img src='./screenshots/v_5.0__1.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tJobInstance>Source Code on Github</a>
 * <a href=http://jan-lolling.de//talend/cimt_framework/talend_job_instance_components_usecases.pdf>Documentation Concept and Use Cases</a>
 * <a href=https://github.com/jlolling/talendcomp_tJobInstance/blob/master/doc/tJobInstanceStart.pdf>Documentation Components</a>

#### Release Notes

##### 5.0 - 2016-04-18 10:46:10
* Check of the current job instance runs as singleton instance
* Return value to steer the job in case of Job runs (or not) as singleton
### Compatible
 -  5.4 (obsolete)
 -   5.5 (obsolete)
 -   5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)