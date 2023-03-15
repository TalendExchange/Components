# tdgadmin
   
Headquartered in Princeton, New Jersey, The Digital Group was incorporated in 1999. Today The Digital Group (T/DG) is the leading provider of a broad range of Information Technology services. With offices in US, India, Australia, Fiji and Sri Lanka T/DG provide support from the conceptualization phase, leading to development and operations. The team have been consistently delivering industry leading solutions to its valued customers for over a decade.

The Digital Group is a certified SEI-CMMi Level 5 for Development (DEV) and CMMi Level 3 for Services (SVC) version 1.3 along with certifications in ISO 9001:2008, ISO 20000-1:2011, ISO 27001:2013 and SSAE 16, Type II.

With significant experience, timely results and up-gradation, T/DG has successfully retained its earlier clients and continues to incorporate new ones. The team consists of domain and technical experts, who facilitate world-class consulting solutions to its clients. The primary strength of their consultants is to work seamlessly with client organizations to optimize existing resources and implement improvement strategies successfully.
     <http://www.thedigitalgroup.com>
  <nospam+talendsolradmin@thedigitalgroup.com>

## <a href='./components/Talend Solr High Speed Insert Plugin/readme.md'><img src='./components/Talend Solr High Speed Insert Plugin/logo.jpg' width='40' height='40'> Talend Solr High Speed Insert Plugin</a>
 :warning: Compatibility not known

Function : To add new documents to solr index.

Purpose\t: tRapidSolrInsert help to add  new documents to solr index using concurrent APIs

Important Terminology
- Schema : A schema is a row description, i.e. it defines the number of fields to be processed and passed on to the next component. The schema is either Built-in or stored remotely in the Repository. 
\tFollowing click events are supported:
\t\t•\tClick Edit Schema to make changes to the schema. If the current schema is of the Repository type, three options are available:
\t\t•\tView schema: choose this option to view the schema only.
\t\t•\tChange to built-in property: choose this option to change the schema to Built-in for local changes.
\t\t•\tUpdate repository connection: choose this option to change the schema stored in the repository and decide whether to propagate the changes to all the Jobs upon completion. If you just want to propagate the changes to the current Job, you can select No upon completion and choose this schema metadata again in the Repository Content window.
\t\t•\tBuilt-in: The schema will be created and stored locally for this component only. 
\t\tRepository: The schema already exists and is stored in the Repository, hence can be reused in various projects and Job flowcharts. 

- Queue Size : Number of docs in one queue\t\t
- Action : Insert, Delete, Delete before Insert
- Thread Count : Number of threads to running while indexing on solr
- Advanced settings : tStatCatcher Statistics : Select this check box to collect the log data at component level. 

Usage : This component can be used as intermediate step in a data flow.
Limitation\t: n/a

<img src='./components/Talend Solr High Speed Insert Plugin/sample.jpg'>

## <a href='./components/Talend Solr High Speed Query Plugin/readme.md'><img src='./components/Talend Solr High Speed Query Plugin/logo.jpg' width='40' height='40'> Talend Solr High Speed Query Plugin</a>
 :warning: Compatibility not known

Function : To Update existing solr docs.


Purpose\t: tRapidSolrUpdate help to Update existing solr documents, 

Important Terminologies :
- Schema : A schema is a row description, i.e. it defines the number of fields to be processed and passed on to the next component. The schema is either Built-in or stored remotely in the Repository. 
\tFollowing click events are supported:
\t\t•\tClick Edit Schema to make changes to the schema. If the current schema is of the Repository type, three options are available:
\t\t•\tView schema: choose this option to view the schema only.
\t\t•\tChange to built-in property: choose this option to change the schema to Built-in for local changes.
\t\t•\tUpdate repository connection: choose this option to change the schema stored in the repository and decide whether to propagate the changes to all the Jobs upon completion. If you just want to propagate the changes to the current Job, you can select No upon completion and choose this schema metadata again in the Repository Content window.
\t\t•\tBuilt-in: The schema will be created and stored locally for this component only. 
\t\tRepository: The schema already exists and is stored in the Repository, hence can be reused in various projects and Job flowcharts. 
\t\t\t
- Thread Count : Number of threads to running while indexing on solr
- Advanced settings : tStatCatcher Statistics\tSelect this check box to collect the log data at component level. 

Usage : This component can be used as intermediate step in a data flow.
Limitation\t: n/a

<img src='./components/Talend Solr High Speed Query Plugin/sample.jpg'>

## <a href='./components/Talend Solr High Speed Update Component/readme.md'><img src='./components/Talend Solr High Speed Update Component/logo.jpg' width='40' height='40'> Talend Solr High Speed Update Component</a>
 :warning: Compatibility not known

Function : To update existing documents in solr index.

Purpose\t: tRapidSolrUpdate help to Update existing solr documents using concurrent APIs

Important Terminology
- Schema : A schema is a row description, i.e. it defines the number of fields to be processed and passed on to the next component. The schema is either Built-in or stored remotely in the Repository. 
\tFollowing click events are supported:
\t\t•\tClick Edit Schema to make changes to the schema. If the current schema is of the Repository type, three options are available:
\t\t•\tView schema: choose this option to view the schema only.
\t\t•\tChange to built-in property: choose this option to change the schema to Built-in for local changes.
\t\t•\tUpdate repository connection: choose this option to change the schema stored in the repository and decide whether to propagate the changes to all the Jobs upon completion. If you just want to propagate the changes to the current Job, you can select No upon completion and choose this schema metadata again in the Repository Content window.
\t\t•\tBuilt-in: The schema will be created and stored locally for this component only. 
\t\tRepository: The schema already exists and is stored in the Repository, hence can be reused in various projects and Job flowcharts. 

- Thread Count : Number of threads to running while indexing on solr
- Advanced settings : tStatCatcher Statistics : Select this check box to collect the log data at component level. 

Usage : This component can be used as intermediate step in a data flow.
Limitation\t: n/a

<img src='./components/Talend Solr High Speed Update Component/sample.jpg'>
