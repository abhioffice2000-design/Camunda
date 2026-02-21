FROM docker.elastic.co/elasticsearch/elasticsearch:8.11.0

EXPOSE 9200
EXPOSE 9300

ENV discovery.type=single-node
ENV xpack.security.enabled=false
ENV cluster.routing.allocation.disk.threshold_enabled=false