FROM openjdk:17-jdk-slim

#Information around who maintains the image
MAINTAINER Faizan khan

COPY target/loans-0.0.1-SNAPSHOT.jar loans-0.0.1-SNAPSHOT.jar

# execute the application
ENTRYPOINT ["java", "-jar", "loans-0.0.1-SNAPSHOT.jar"]