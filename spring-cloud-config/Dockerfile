FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY target/spring-cloud-config-*.jar /cloud-config.jar
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /app.jar" ]
