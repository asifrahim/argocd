FROM fundingsocietiesdocker/openjdk19-alpine
WORKDIR /opt
ENV PORT 8085
EXPOSE 8085
COPY target/*.jar /opt/app.jar
ENTRYPOINT exec java $JAVA_OPTS -jar app.jar