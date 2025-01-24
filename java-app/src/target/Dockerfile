# Use an official OpenJDK runtime as the base image
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container
COPY target/java-app.jar /app/java-app.jar

# Expose the application's port (if applicable)
EXPOSE 8080

# Command to run the Java application
CMD ["java", "-jar", "java-app.jar"]
