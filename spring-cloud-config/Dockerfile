FROM openjdk:8-jdk-alpine
COPY target/spring-cloud-config-1.0.jar /cloud-config.jar
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /cloud-config.jar" ]
