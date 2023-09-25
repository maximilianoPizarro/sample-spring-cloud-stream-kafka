FROM openjdk:17
RUN mkdir -p /usr/src/myapp
COPY /target/*.jar /usr/src/myapp
WORKDIR /usr/src/myapp
CMD ["java", "-jar","stock-service-1.0-SNAPSHOT.jar"]