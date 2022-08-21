FROM openjdk:8-jdk-alpine
COPY target/eureka-1.0.jar /eureka.jar
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /eureka.jar" ]
