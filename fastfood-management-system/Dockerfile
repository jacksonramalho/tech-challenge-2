FROM amazoncorretto:17-alpine-jdk
ADD target/tech.challenge-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
EXPOSE 8080