FROM openjdk:8

COPY ./config-server-*.jar config-server.jar

EXPOSE 1000

CMD ["java","-jar","-Dspring.profile.active=dev","config-server.jar"]