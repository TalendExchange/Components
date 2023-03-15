## <img src='./logo.jpg' width='40' height='40'>Kudu Output

### Overview
**Apache Kudu** is a revolutionary new columnar store for Hadoop that enables the powerful combination of fast analytics on fast data. Kudu complements the existing Hadoop storage options, **HDFS** and **Apache HBase**. Additional information on **Apache Kudu**, its architecture and use cases can be found at (http://getkudu.io/).

Onepoint provides two components that enable reading data from and writing data to Kudu which is the first native Hadoop storage engine that supports both low-latency random access and high-throughput analytics. This enables seamless integration between your organization's multiple, heterogeneous data source and Kudu.

### Details
These components enable organization's to create a data pipeline between existing data sources and Kudu thus enabling fast analytics and fast data from sources such as Internet of Things, wearables, machine data among others. They enable all main CRUD operations of Create, Read, Update and delete.

Kudu Output
===========
The Kudu Output component supports table creation operations as well as 4 record based operations: 
-   **create** 
-   **insert**
-   **delete** 
-   **upsert** 
This component also allows detailed error handling when the AUTO_FLUSH mode is turned on.

Kudu Input
==========
The Kudu Input component supports table scanning, but also the usage of an unlimited number of Kudu queries. 
### Images
<a href='./screenshots/v_0.2__20.jpg'><img src='./screenshots/v_0.2__20.jpg' ></a>
<a href='./screenshots/v_0.2__19.jpg'><img src='./screenshots/v_0.2__19.jpg' ></a>
<a href='./screenshots/v_0.2__18.jpg'><img src='./screenshots/v_0.2__18.jpg' ></a>
<a href='./screenshots/v_0.2__17.jpg'><img src='./screenshots/v_0.2__17.jpg' ></a>
<a href='./screenshots/v_0.2__16.jpg'><img src='./screenshots/v_0.2__16.jpg' ></a>


### Install Instructions
Before installing make sure that you have defined the components folder in your Talend project. Then unzip the file and copy the folder with name tKuduOutput to your Talend components folder. After this restart Talend Studio.
### Resources
 * <a href=http://www.onepointltd.com/community-development/>Onepoint Webpage</a>
 * <a href=http://getkudu.io/>Kudu Webpage</a>

#### Release Notes

##### 0.1 - 2016-06-02 16:50:26
**Kudu Output** allows **inserting**, **updating** and **deleting** records. It also supports a reject connector which works only in AUTO FLUSH mode.
##### 0.2 - 2016-11-01 10:33:11
The new version of the Kudu Output bundles the Apache Kudu client in version **1.0.1**. I.e. this version supports of Apache Kudu version 1.0.1.
The component now supports connections to **multiple servers** and it also supports the **upsert** operation.
### Compatible
 -  6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)