FROM openjdk:8-jre-alpine

ARG JAR_FILE=*.jar

COPY ${JAR_FILE} application.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","application.jar"]

