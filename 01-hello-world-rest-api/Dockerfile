FROM openjdk:8-jdk-alpine

ADD target/hello-world-rest-api.jar hello-world-rest-api.jar

# It's the information/metadata only (this port won't be accessible outside of container)
# Container will run on this port ONLY internally
EXPOSE 8080

ENTRYPOINT ["sh", "-c", "java -jar /hello-world-rest-api.jar"]