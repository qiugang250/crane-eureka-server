FROM java:8-jre-alpine
VOLUME /tmp
ADD @project.build.finalName@.jar app.jar
RUN bash -c 'touch /app.jar'
EXPOSE 8761
ENTRYPOINT ["java","-jar","/app.jar"]