FROM docker.elastic.co/elasticsearch/elasticsearch:7.3.1

RUN ./bin/elasticsearch-plugin install --batch https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.3.1/elasticsearch-analysis-ik-7.3.1.zip
EXPOSE 9200 9300
