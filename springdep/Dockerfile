FROM openjdk:21-jdk-slim
ARG JAR_FILE=target/springdep-0.0.1.jar
COPY ${JAR_FILE} app_springdep.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","app_springdep.jar"]