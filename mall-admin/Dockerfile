FROM java:8
VOLUME /tmp
ADD *.jar /app.jar
ENV LANG C.UTF-8
ENV TZ=Asia/Shanghai
ENTRYPOINT [ "java","-jar","/app.jar"]