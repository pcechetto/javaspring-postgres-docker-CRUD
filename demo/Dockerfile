FROM openjdk:17-jdk-alpine

COPY target/demo-0.0.1-SNAPSHOT.jar app-1.0.0.jar

EXPOSE 8080

ENTRYPOINT [ "java", "-jar", "app-1.0.0.jar" ]