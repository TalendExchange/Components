## <img src='./logo.jpg' width='40' height='40'>Hortonwork-2.3-custom-distribution

### Overview
This extension allows connecting to the HDP 2.3 Hadoop distribution
### Images



### Install Instructions
[Importing a Custom Hadoop Distibution to Talend Studio](https://help.talend.com/display/KB/Importing+a+Custom+Hadoop+Distribution+to+Talend+Studio)

#### Release Notes

##### 1.0.1 - 2015-08-16 11:52:15
Release notes
========

Pig
---

* When using an HCatStorer or HCatLoader, you may encounter the error "org.apache.hcatalog.pig not found".  The workaround is to change from Custom Distribution to Hortonworks and Version to 2.2, then change back to Custom Distribution.  This has been fixed in 5.6.3, 6.0.1 and onwards.

* The following Hadoop properties may need to be added to pig components Hadoop Properties (the values here are for the HDP2.3 sandbox, your installed cluster may vary):

```
"yarn.application.classpath" "/usr/hdp/current/hadoop-client/*,/usr/hdp/current/hadoop-client/lib/*,/usr/hdp/current/hadoop-hdfs-client/*,/usr/hdp/current/hadoop-hdfs-client/lib/*,/usr/hdp/current/hadoop-yarn-client/*,/usr/hdp/current/hadoop-yarn-client/lib/*,/usr/hdp/current/hadoop-mapreduce-client/lib/*,/usr/hdp/current/hadoop-mapreduce-client/*"
```

```
"mapreduce.jobhistory.intermediate-done-dir" "/mr-history/tmp"
```

```
"mapreduce.jobhistory.done-dir" "/mr-history/done"
```

Hive
----

* The **parquet-hadoop-\\*.jar** file was renamed to **parquet-hive-\\*.jar** for compatibility reasons.  When using parquet and hive, the **fs.defaultFS** property on the cluster must not be final.
### Compatible
 -  5.6 (obsolete)
 -   6.0 (obsolete)
 -   6.1 (obsolete)
 -   6.2 (obsolete)