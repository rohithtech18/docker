FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} apigatewayapp.jar
ENTRYPOINT ["java","-jar","/apigatewayapp.jar"]