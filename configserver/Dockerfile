#Start with a base image containing Java runtime
FROM openjdk:17-jdk-slim

#Information around who maintains the image
MAINTAINER Faizan khan

# Add the application's jar to the image
COPY target/configserver-0.0.1-SNAPSHOT.jar configserver-0.0.1-SNAPSHOT.jar

# execute the application
ENTRYPOINT ["java", "-jar", "configserver-0.0.1-SNAPSHOT.jar"]