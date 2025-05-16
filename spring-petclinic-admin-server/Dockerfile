FROM openjdk:11-jre
<<<<<<< HEAD
ENV SPRING_PROFILES_ACTIVE docker
WORKDIR /app
COPY ./target/*.jar /app.jar
=======
WORKDIR /app
ENV SPRING_PROFILES_ACTIVE docker
COPY ./target/*.jar app.jar
>>>>>>> feature/msp-6
EXPOSE 9090
CMD  ["java", "-jar", "./app.jar"]