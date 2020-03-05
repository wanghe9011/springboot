FROM java:8
ARG JAR_FILE
ADD target/$JAR_FILE /opt/app.jar
ENTRYPOINT ["java","-jar","/opt/app.jar"]
