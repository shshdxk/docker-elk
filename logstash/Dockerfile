FROM docker.elastic.co/logstash/logstash:6.4.0
USER root
RUN usermod -u 888 logstash && groupmod -g 888 logstash
USER logstash:logstash