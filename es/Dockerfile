FROM docker.elastic.co/elasticsearch/elasticsearch:5.6.0

COPY ./vector-scoring-5.6.0.zip /usr/share/elasticsearch/
RUN  /usr/share/elasticsearch/bin/elasticsearch-plugin install file:///usr/share/elasticsearch/vector-scoring-5.6.0.zip
CMD ["/usr/share/elasticsearch/bin/elasticsearch"]

