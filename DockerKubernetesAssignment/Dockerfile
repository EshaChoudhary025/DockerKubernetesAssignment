
FROM openjdk:11-slim

WORKDIR /app

COPY target/DockerKubernetesAssignment-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]