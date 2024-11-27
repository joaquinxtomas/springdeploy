FROM openjdk:21-jdk-slim
ARG JAR_FILE=spring-deploy-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app_springdeploy.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_springdeploy.jar"]