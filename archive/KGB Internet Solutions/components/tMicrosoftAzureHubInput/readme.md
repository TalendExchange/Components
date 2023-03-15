## <img src='./logo.jpg' width='40' height='40'>tMicrosoftAzureHubInput

### Details
Please edit the Default Marketing Plan and put a detailed description of your product listing including product features and benefits.
### Images



### Install Instructions
Azure Event Hub does not keep track of which messages you have received like the service bus does.  The consuming application is responsible for keeping track of which messages it has already received.  Two common ways are to 1) keep track of the event time stamps you have received (may be duplicate records with same time stamp), or 2) keep the last offset received for each partition.  Azure Event Hub ALWAYS creates at least two partitions.

Unless you want to retrieve every message in the named event hub, you'll want to either provide a time filter or an offset filter.  An offset filter is a Map<String,String> type where the first string is the partition number ("0","1","2"...) and the second string is the offset.  The time stamp and offset are outputs along with the message, so keep track of those values somewhere (file, db) so you can restart the job later without re-retrieving those same messages.

#### Release Notes

##### 0.1 - 2017-10-31 04:45:49
Retrieve events from Azure Event Hub.
### Compatible
 -