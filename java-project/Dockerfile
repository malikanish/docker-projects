# Use an official OpenJDK runtime as a parent image
FROM openjdk:latest

# Set the working directory in the container
WORKDIR /app

# Copy the source code into the container
COPY src/Main.java .

# Compile the Java source code
RUN javac Main.java

# Command to run thee application
CMD ["java", "Main"]

