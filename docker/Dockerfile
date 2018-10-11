FROM java:8-jre-alpine
VOLUME /tmp
RUN mkdir /app && mkdir /log
ADD @project.build.finalName@.jar /app 
EXPOSE 8761
ENTRYPOINT java -Xmx1000M -Xms1000M -jar  -Duser.timezone=GMT+8 /app/*jar