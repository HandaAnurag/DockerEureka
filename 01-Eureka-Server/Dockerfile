FROM openjdk:17-jdk-alpine
EXPOSE 8761
COPY ./target/EurekaDocker.jar EurekaDocker.jar
ENTRYPOINT ["java","-jar","EurekaDocker.jar"]
