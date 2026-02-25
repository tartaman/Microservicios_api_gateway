 #Use an official OpenJDK runtime as a parent image
FROM eclipse-temurin:21-jre-alpine


 #Copy the JAR file to the container
COPY target/escuela_modelo-0.0.1-SNAPSHOT.jar escuela_modelo-0.0.1-SNAPSHOT.jar

 #Run the application
ENTRYPOINT [ "java","-jar","escuela_modelo-0.0.1-SNAPSHOT.jar" ]


 #Imagen con JDK (necesario para mvn)

