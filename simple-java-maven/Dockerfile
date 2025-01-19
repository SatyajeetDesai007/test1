
# Use a Tomcat base image
FROM tomcat:9.0-jdk11

# Copy your WAR file into Tomcat's webapps folder
COPY target/simple-java-maven.war /usr/local/tomcat/webapps/

# Expose the port that Tomcat is listening on (8080 by default)
EXPOSE 8080

# Start Tomcat
CMD ["catalina.sh", "run"]


