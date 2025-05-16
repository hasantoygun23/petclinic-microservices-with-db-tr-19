FROM openjdk:11-jre
WORKDIR /app
ENV SPRING_PROFILES_ACTIVE docker,mysql
COPY ./target/*.jar app.jar
EXPOSE 8081
CMD  ["java", "-jar", "./app.jar"]