FROM openjdk:8-jre-alpine
VOLUME /tmp
ADD target/*.jar app.jar
RUN sh -c 'touch /app.jar'
EXPOSE 8761
ENTRYPOINT ["java","-jar","/app.jar"]