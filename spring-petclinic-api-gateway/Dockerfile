FROM openjdk:11-jre
WORKDIR /app
ENV SPRING_PROFILES_ACTIVE docker
COPY ./target/*.jar app.jar
EXPOSE 8080
CMD  ["java", "-jar", "./app.jar"]