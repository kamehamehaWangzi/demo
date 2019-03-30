FROM java:8

ADD demo-0.0.1-SNAPSHOT.war /app.war

EXPOSE 8080

ENTRYPOINT ["/usr/bin/java","-jar","app.war"]