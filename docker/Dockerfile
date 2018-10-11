FROM anapsix/alpine-java:8
RUN mkdir /app && mkdir /log
VOLUME /tmp
ADD @project.build.finalName@.jar /app 
EXPOSE 8761
ENTRYPOINT java -Xmx1000M -Xms1000M -jar  -Duser.timezone=GMT+8 /app/*jar