# cantoine
  <http://www.talend.com>
  <nospam+cantoine@talend.com>

## <a href='./components/tAsterDataNClusterLoader/readme.md'><img src='./components/tAsterDataNClusterLoader/logo.jpg' width='40' height='40'> tAsterDataNClusterLoader</a>
 :warning: Compatibility not known

The tAsterDataNClusterLoader component helps you to benefit of the nClusterLoader API and Utility to bulk load your data into your AsterData nCluster Database.
<img src='./components/tAsterDataNClusterLoader/sample.jpg'>

## <a href='./components/tCassandraOutput/readme.md'><img src='./components/tCassandraOutput/logo.jpg' width='40' height='40'> tCassandraOutput</a>
 :warning: Compatibility not known

This CassandraOuput component is a component to write into Cassandra database.

Cassandra database is an Apache project; you might find interesting information on the website of this project : http://cassandra.apache.org/

Quick summary about Cassandra : The Apache Cassandra Project develops a highly scalable second-generation distributed database, bringing together Dynamo's fully distributed design and Bigtable's ColumnFamily-based data model. 


Cassandra is in use at Digg, Facebook, Twitter, Reddit, Rackspace, Cloudkick, Cisco, SimpleGeo, Ooyala, OpenX, and more companies that have large, active data sets. The largest production cluster has over 100 TB of data in over 150 machines. 

# Rich Data Model
Allows efficient use for many applications beyond simple key/value.

# Elastic
Read and write throughput both increase linearly as new machines are added, with no downtime or interruption to applications. 

All rewards should goes to Richie BALDWIN who has built this component in a day :)
<img src='./components/tCassandraOutput/sample.jpg'>

## <a href='./components/tRDSPostgresqlBulkExec/readme.md'><img src='./components/tRDSPostgresqlBulkExec/logo.jpg' width='40' height='40'> tRDSPostgresqlBulkExec</a>
 :warning: Compatibility not known

tRDSPostgresqlBulkExec is the component to leverage the COPY COMMAND through the Postgresql Client in RDS. 
In RDS the COPY COMMAND can not be called through the classical way -> SQL Query (RDS is limited and different than Postgresql and Redshift on that particular requirement). 
Since this component is taking advantage of the psql binary; you will have to install the the Postgresql Client package; and then specify the PATH of the bin folder where to find the psql binary.
<img src='./components/tRDSPostgresqlBulkExec/sample.jpg'>
