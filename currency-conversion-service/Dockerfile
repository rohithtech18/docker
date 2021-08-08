FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} ccsapp.jar
ENTRYPOINT ["java","-jar","/ccsapp.jar"]