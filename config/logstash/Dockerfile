FROM docker.elastic.co/logstash/logstash-oss:6.1.0
COPY logstash.yml /usr/share/logstash/config/
COPY pipelines.yml /usr/share/logstash/config/
COPY myapp.log /usr/tmp/