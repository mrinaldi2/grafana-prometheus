FROM openjdk:16-alpine3.13
RUN mkdir /app
WORKDIR /app
EXPOSE 8080
EXPOSE 8081
COPY *.jar server.jar
ENTRYPOINT ["java", "-jar", "server.jar"]