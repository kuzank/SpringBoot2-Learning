FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD chapter2-0-2-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]