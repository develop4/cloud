FROM java:8-jre

ADD configserver-0.0.1-SNAPSHOT.jar app.jar
RUN bash -c 'touch /app.jar'

ADD docker-entrypoint.sh docker-entrypoint.sh
RUN chmod +x /docker-entrypoint.sh

ENTRYPOINT ["/docker-entrypoint.sh"]

EXPOSE 8888