FROM solr:8.3.0
COPY --chown=solr configurations/ /var/solr/data/
USER root
RUN cp /opt/solr-8.3.0/dist/solr-analytics-* /opt/solr-8.3.0/server/solr-webapp/webapp/WEB-INF/lib/
RUN echo 'SOLR_OPTS="$SOLR_OPTS -Dsolr.data.dir=/var/solr/data"' >> /etc/default/solr.in.sh
USER solr
