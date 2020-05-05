ARG ELK_VERSION

FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

COPY logstash.yml /usr/share/logstash/config/

COPY pipeline /usr/share/logstash/pipeline
