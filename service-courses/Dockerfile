FROM openjdk:17-alpine

WORKDIR /opt/server
COPY ./target/service-courses-0.0.1-SNAPSHOT.jar server.jar

EXPOSE 8081

ENTRYPOINT ["java", "-jar", "server.jar"]
