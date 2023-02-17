# Alpine Linux with OpenJDK JRE
FROM bellsoft/liberica-openjdk-alpine:17

# Copy war file
COPY pryAzure01-0.0.1-SNAPSHOT.jar /usr/share/sample.war

# run the app
CMD ["/usr/bin/java", "-jar", "/usr/share/sample.war"]