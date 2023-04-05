FROM open-liberty:full-java11-openj9
COPY --chown=1001:0 modresorts-1.0.war /config/dropins
COPY --chown=1001:0 server.xml /config/
RUN configure.sh
