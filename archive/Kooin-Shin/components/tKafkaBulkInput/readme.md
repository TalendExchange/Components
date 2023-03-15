## <img src='./logo.jpg' width='40' height='40'>tKafkaBulkInput

### Overview
This component provide interval time opertation to process kafka bulk with users.
Basically you can be setting start date and end date on UI input form from component tap. Also if you are needed to set polling timeout and polling count, you can do it.
Normally You have only to input interval of time value. If you need to be set detail configuration of polling, you can configurate that. polling timeout is timeout value per one polling. polling count is polling count. In case of huge data polling process, data could't be fetched at once with single polling and sometimes could be empty. because of this, you can setting this value properly.

### Details
You can be using stored stream service of kafka.
You can be setting multiple broker of kafka server.
You can be extracting data with interval time of your needs.
### Images
<a href='./screenshots/v_v1.01__3.jpg'><img src='./screenshots/v_v1.01__3.jpg' ></a>
<a href='./screenshots/v_0.94__2.jpg'><img src='./screenshots/v_0.94__2.jpg' ></a>
<a href='./screenshots/v_0.93__1.jpg'><img src='./screenshots/v_0.93__1.jpg' ></a>


### Install Instructions
Download this artifact.
Extract component files from zip file of that.
Copy extracted files to component directory of TOS plugin or custom component directory.
Restart TOS.
And dive into it.
### Resources
 * <a href=https://kafka.apache.org/intro>Kafka home</a>
 * <a href=https://kafka.apache.org/10/javadoc/index.html>Kafka Java API Documentation</a>

#### Release Notes

##### 0.93 - 2020-02-10 00:25:04
First draft of this component.
##### 0.94 - 2020-03-24 00:49:13
To improve consumer configuration detail setting.
You can set configuration with key/value.
##### v1.01 - 2020-05-08 02:27:37
To able to select partition, you can set partitions with comma seperated number.
To improve component inner logic.
### Compatible
 -  6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)
 -   6.3 (obsolete)
 -   6.4 (obsolete)
 -  6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2
 - 7.3