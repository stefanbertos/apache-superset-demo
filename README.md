# apache-superset-demo

https://superset.apache.org/docs/intro/

To start all containers use: `docker-compose up -d`

To stop all containers use: `docker-compose down`

docker-compose build --force-rm

## When all is up you can access:
- Elasticsearch at http://localhost:9200/
- Kibana at http://localhost:5601
- Superset at http://localhost:8088

https://www.elastic.co/guide/en/kibana/current/connect-to-elasticsearch.html
https://preset.io/blog/2019-12-16-elasticsearch-in-superset/


elasticsearch+http://elastic:changeme@localhost:9200/

elasticsearch+http://{user}:{password}@{host}:9200/

elasticsearch+http://elastic:changeme@device1:9200/