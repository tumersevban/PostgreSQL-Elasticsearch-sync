# PostgreSQL-Elasticsearch Sync

## Purpose of project:
Purpose of project is create synchronization between Elasticsearch and PostgreSQL. Data in PostgreSQl will sent Elasticsearch.

*_Note: Please know that It is not real time sync. Any chnage in postgresql, Logstash must run again._*

## Which tool used:
* Docker
* Logstash
* PostgreSQL 
* Elasticsearch 

## Steps:

##### 1. Install necessary environment.

[Docker](https://docs.docker.com/engine/install/), [Elasticsearch](https://www.elastic.co/guide/en/elasticsearch/reference/current/install-elasticsearch.html) and  [Logstash](https://www.elastic.co/guide/en/logstash/current/installing-logstash.html) must be installed.

##### 2. Create database in Docker

[This link](https://dev.to/andre347/how-to-easily-create-a-postgres-database-in-docker-4moj) helps you during the step. 

##### 3. Create ETL pipeline.

##### 3. Install JDBC driver for PostgreSQl
You need to install jdbc driver from [here. ](https://jdbc.postgresql.org/download/) 

##### 4. Run it.

##### 5. Check the Elasticsearch side.
