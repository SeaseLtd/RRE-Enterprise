<img src="img/logo-RREE-gradient.png" alt="RRE-Enterprise Logo" title="RRE-Enterprise: the next generation of free Search Quality Evaluation Tools for Elasticsearch/Apache Solr search engines" width="200" align="right"/>

Rated Ranking Evaluator-Enterprise
==========================

*the next generation of free Search Quality Evaluation Tools for Elasticsearch/Apache Solr search engines*

This repository contains the docker compose instructions to pull RRE-Enterprise from docker-hub and run it locally.
For additional information:

*Coming Soon

## How To Run RRE-Enterprise   

To start the RRE-Enterprise ecosystem:

```
docker-compose up 
```  
  
Now you need to activate RRE-Enterprise with a free product-key:
[Get a free product-key!](https://sease.io/draft-rre-form2)  
```
curl -X POST -F 'user=<userMail>' -F 'productKey=<productKey>' http://localhost:8081/1.0/rre-enterprise-api/license-api/activate
```

* RRE-Enterprise runs at http://localhost:3001
  
For more information on how to use RRE-Enterprise we have prepared this Blog Post series:

*Coming Soon
  
To destroy your environment (including any volumes created like the mysql db), just run:
```
docker-compose down -v
```  
