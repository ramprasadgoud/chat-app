FROM amd64/openjdk:21-jdk-slim

WORKDIR /app
COPY target/chat-app-backend-3.4.0.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
