FROM openjdk:8-jdk

#VOLUME /tmp

ADD target/gs-serving-web-content-0.1.0.jar /app.jar

#RUN sh -c 'touch /portal-content-service.war'

ENV JAVA_OPTS=""

ENTRYPOINT [ "bash", "-c", "java -jar /app.jar" ]
