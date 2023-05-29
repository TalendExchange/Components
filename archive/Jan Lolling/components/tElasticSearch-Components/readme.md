## <img src='./logo.jpg' width='40' height='40'>tElasticSearch-Components

### Overview
Following components supports the work with ElasticSearch:
tElasticSearchIndexOutput - write documents
tElasticSearchIndexErrors - returns all errors occurs while the last indexing with tElasticSearchIndexOutput
tElasticSearchRequest - Send arbitrary to ElasticSearch

All components provides client based load balancing and failover.
These components uses the latest REST API from ElasticSearch.
The communication can be encrypted and secured with authentication.
### Details
* Provides all necessary functionality to work with ElasticSearch in Data Integration jobs. 
### Images
<a href='./screenshots/v_3.3__9.jpg'><img src='./screenshots/v_3.3__9.jpg' ></a>
<a href='./screenshots/v_3.3__8.jpg'><img src='./screenshots/v_3.3__8.jpg' ></a>
<a href='./screenshots/v_3.3__7.jpg'><img src='./screenshots/v_3.3__7.jpg' ></a>
<a href='./screenshots/v_3.2__6.jpg'><img src='./screenshots/v_3.2__6.jpg' ></a>
<a href='./screenshots/v_3.2__5.jpg'><img src='./screenshots/v_3.2__5.jpg' ></a>


### Resources
 * <a href=https://github.com/jlolling/talendcomp_tElasticSearch/blob/master/doc/tElasticSearch.pdf>Documentation</a>
 * <a href=https://github.com/jlolling/talendcomp_tElasticSearch>Source Code</a>

#### Release Notes

##### 2.2 - 2020-03-25 19:54:26
* Release already in productive use
* Log4J removed to prevent compatibility problems with Talend 7.3.1
##### 3.2 - 2021-09-09 06:35:18
* Bugfix for authetification on ElasticSearch server
* Newest API of ElasticSearch Client
##### 3.3 - 2021-12-14 15:02:36
* log4j removed
### Compatible
 - 6.5 (retired)
 -  7.0 (retired)
 -  7.1 (retired)
 - 7.2
 - 7.3
 - 8.0