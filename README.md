# Data Analytics, Aggregation & Visualisation Starter Kit

This project provides basic components to start working with Data Analytics, Aggregation & Visualisation.
It can be used for DevOPS, Application Statistics etc...

It's build on top of great stack provided by [Elastic](https://www.elastic.co/) company:
- [ElasticSearch](https://www.elastic.co/products/elasticsearch "ElasticSearch") used for deep search and data analytics
- [Logstash](https://www.elastic.co/products/logstash "Logstash") used for centralized logging, log enrichment and parsing
- [Kibana](https://www.elastic.co/products/kibana "Kibana") used for powerful and beautiful data visualizations

Expect that essential ELK Stack this starter provides:
- [Redis](http://redis.io/ "Re") used as broker for Logstash logs
- [NGINX](https://www.nginx.com/ "NGINX") used as reverse proxy to Kibana UI

Everything is set up on top of [Docker](https://www.docker.com/ "Docker") containers.

## Example AWS Diagram

![AWS Diagram](https://github.com/Abdizriel/data-analytics-starter-kit/blob/master/diagram.png)
