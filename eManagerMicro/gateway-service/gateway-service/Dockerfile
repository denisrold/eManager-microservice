FROM openjdk:8-jdk-alpine
COPY target/awesome-app-api-gateway-1.0.0-SNAPSHOT.jar service.jar
ENTRYPOINT [ "java","-jar","/service.jar"]