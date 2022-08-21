FROM openjdk:8-jdk-alpine
ADD target/zuul-1.0.jar.jar zuul.jar
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /zuul.jar" ]
