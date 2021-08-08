FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} cesapp.jar
ENTRYPOINT ["java","-jar","/cesapp.jar"]