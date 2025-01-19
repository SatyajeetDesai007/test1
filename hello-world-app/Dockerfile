FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/hello-world-app-0.0.1-SNAPSHOT.war /app/hello-world-app.war

EXPOSE 8080

CMD ["java", "-jar", "hello-world-app.war"]
