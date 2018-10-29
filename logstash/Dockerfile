FROM docker.elastic.co/logstash/logstash:6.4.0
RUN usermod -u 888 logstash && groupmod -g 888 logstash
USER logstash:logstash