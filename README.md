# datawarehouse-modelling
Noob to Experts : Data Modelling concepts for a data-warehouse

## What is a Datawarehouse?
Datawarehouse is an entreprise level data store which stores data related to a specific domain to answer business questions. It is basically used for reporting and analytics. Data present in a datawarehouse is processed and aggregated data which can be directly utilized by reporting or analytical tools or processes.

### Properties of a datawarehouse:
<ul>
  <li>Subject Oriented: It is built for a specific purpose and designed to do certian kind of analytics. e.g different departments in an organization may have different datawarehouse for their own analytics.</li>
  <li>Integrated: It can be prepared from the data which may come from different sources. In other words, datawarehouse contains data which can be obtained from different data sources like transactional databases, datalakes, blob storages, FTP locations etc.</li>
  <li>Non-volatile: Data inside a datawarehouse is non-volatile and it retains historical data.</li>
</ul>

### Benefits of Datawarehouse:
<ul>
  <li>It separates transactional data from analytical data. Analytical data needs faster read capabilities whereas transactional data needs more write capabilities.</li>
  <li>It provides a single point of contact for analytics and reporting.</li>
  <li>It keeps historical data which is used for analytical purpose and predictions.</li>
  <li>Data inside a datawarehouse can serve as input for machine learning models.</li>
</ul>

### OLTP and OLAP
#### OLTP - Online Transactional Processing
OLTP is a transactional database to store frequently changing data. i.e database of a e-commerce website
<ul>
  <li>Operational databases which are used to store transactional data</li>
  <li>Effective in performing CRUD operations</li>
  <li>Prioritises processing transactions</li>
</ul>



#### OLAP - Online Analytical Processing
OLAP is basically an analytical database system which contains historical data. Datawarehouse is an example of OLAP System.
<ul>
  <li>Created to facilitates efficient analysis</li>  
  <li>Data is loaded at a specific time or periodically,usually in batches</li>
  <li>Data is generally denormalized and restructured </li>
<ul>
  
#### Data Modelling in Datawarehouse
  ##### Types of commonly used data models:

