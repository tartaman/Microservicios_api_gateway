# Use an official OpenJDK runtime as a parent image
FROM eclipse-temurin:21-jre-alpine

# Copy the JAR file to the container
COPY target/eurekaserver-0.0.1-SNAPSHOT.jar eurekaserver-0.0.1-SNAPSHOT.jar

# Run the application
ENTRYPOINT [ "java","-jar","eurekaserver-0.0.1-SNAPSHOT.jar" ]