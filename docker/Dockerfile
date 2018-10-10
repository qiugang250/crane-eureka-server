FROM anapsix/alpine-java:8
 
#  后期更改为日志目录,将日志挂载出来
VOLUME /tmp
# 默认工作目录/
ADD @project.build.finalName@.@project.packaging@ /app.jar

EXPOSE 8761

ENTRYPOINT ["java","-jar","/app.jar"]
