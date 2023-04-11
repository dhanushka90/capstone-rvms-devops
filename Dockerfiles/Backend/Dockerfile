# Start with a base image that has Java 17.06 installed
FROM eclipse-temurin:17.0.6_10-jdk-alpine

# Set the working directory
WORKDIR /app

# Copy the jar file into the container
COPY RVMS-Backend-0.0.1-SNAPSHOT.jar app.jar

# Expose the port that the application will run on
EXPOSE 8080

# Run the application when the container starts
CMD ["java", "-jar", "app.jar"]

