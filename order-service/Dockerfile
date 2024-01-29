# Use an official OpenJDK runtime as a base image
FROM openjdk:20
# Set the working directory inside the container
WORKDIR /app
# Copy the application JAR file into the container
COPY target/order-service-1.0-SNAPSHOT.jar /app/app.jar
# Expose the port that the application will run on
EXPOSE 8080
# Define the command to run your application
CMD ["java", "-jar", "app.jar"]