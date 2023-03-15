## <img src='./logo.jpg' width='40' height='40'>tRunTask

### Overview
This component can trigger or check task in the Talend Administration Center.
It helps to create sophisticated job chains because you can detect in the unlimited flexibility the necessary events or parameters to start a task in the TAC.
With the help of this component you can avoid deploying "monster" jobs containing all jobs needed in a complex task. You simply deploy all necessary jobs as tasks and starts them with a another job.
You can stop the "trigger" job and all currently running task will finishes they work without being interrupted.

Because of the check functionality you can create watchdog jobs for important tasks.

### Details
* Run Task
* Provide context parameter to the task
* Check the task status
* Can execute the requests synchronously or ansynchronously
* Can handle errors while the communication with the TAC
* Starting with Talend release 5.6.1 it returns the real exit code of a job
### Images
<a href='./screenshots/v_2.3__4.jpg'><img src='./screenshots/v_2.3__4.jpg' ></a>
<a href='./screenshots/v_2.3__3.jpg'><img src='./screenshots/v_2.3__3.jpg' ></a>
<a href='./screenshots/v_2.2__2.jpg'><img src='./screenshots/v_2.2__2.jpg' ></a>
<a href='./screenshots/v_2.2__1.jpg'><img src='./screenshots/v_2.2__1.jpg' ></a>


### Resources
 * <a href=http://jan-lolling.de/talend/components/help/tRunTask.pdf>Documentation</a>
 * <a href=https://github.com/jlolling/talendcomp_tRunTask>Source Code on Github</a>

#### Release Notes

##### 2.2 - 2016-03-10 21:21:52
* Fixes an issue with the synchronous run mode: the exit code from the job is wrong.
* Repeats errounous run attempts with a full check of the task status. This avoids problems because of some misleading status information provided by the TAC
##### 2.3 - 2016-04-25 21:18:58
* Bug fixed: a particular errors while communicating with the TAC was not recognised. Especcially in Talend release 5.6.2 the TAC responds sometimes an error when requesting the task detailed execution status. A retry of the request results in a correct response. The retry can be configured in the advanced settings of the component.
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