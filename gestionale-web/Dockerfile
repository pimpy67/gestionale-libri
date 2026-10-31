FROM eclipse-temurin:21-jre-jammy
WORKDIR /app
COPY target/gestionale-web-1.0.0.jar app.jar
EXPOSE 8082
ENTRYPOINT ["java", "-jar", "app.jar", "--spring.profiles.active=prod"]
