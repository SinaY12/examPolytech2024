FROM openjdk:8-jdk-alpine

LABEL maintainer="yanis"

WORKDIR /usr/src/app

COPY target/*.jar app.jar

CMD ["java", "-jar", "app.jar"]