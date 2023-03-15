## <img src='./logo.jpg' width='40' height='40'>tMicrosoftAzureMQInput

### Details
Please edit the Default Marketing Plan and put a detailed description of your product listing including product features and benefits.
### Images



### Install Instructions
Receive messages from the Azure Service Bus.
Azure Service Bus supports two read modes, PEEKLOCK and RECEIVEANDDELETE.  PEEKLOCK requires an explicit commit, for each row, and isn't batched, which significantly decreases performance, especially on high latency networks.
Batching inputs significantly improves performance.  For best performance, use RECEIVEANDDELETE with batched records.  If there are not enough records to complete the batch, Azure responds with what it has available.


#### Release Notes

##### 0.1 - 2017-10-31 05:19:50
Receive messages from Microsoft Azure Service Bus
### Compatible
 -  6.3 (obsolete)