FROM openjdk:8-jre-alpine
RUN mkdir /app && mkdir /log
VOLUME /tmp
ADD target/* /app
EXPOSE 8761
ENTRYPOINT ["java","-jar","/*.jar"]