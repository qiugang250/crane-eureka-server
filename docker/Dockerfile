FROM anapsix/alpine-java:8
RUN mkdir /app && mkdir /log
VOLUME /tmp
ADD @project.build.finalName@.@project.packaging@ /app
EXPOSE 8761
ENTRYPOINT ["java","-jar","/app/*.jar"]