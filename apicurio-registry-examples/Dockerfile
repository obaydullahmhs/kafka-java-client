# Use an official OpenJDK runtime as a parent image
FROM eclipse-temurin:17.0.10_7-jdk

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file into the container
COPY out/artifacts/apicurio_registry_examples_jar/apicurio-registry-examples.jar /app/registry.jar

# Specify the command to run the JAR file
CMD ["java", "-jar", "registry.jar"]
