FROM openjdk:11-jre
EXPOSE 8080
ADD service-a/target/service-a-0.0.1-SNAPSHOT.jar /app
WORKDIR /app
CMD java -jar service-a-0.0.1-SNAPSHOT.jar
