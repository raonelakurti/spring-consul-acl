FROM openjdk:8-jdk-alpine
#FROM iad.ocir.io/oalprod/jdk11-oal:11.0.3
VOLUME /tmp
ADD target/account-service-1.3.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]
EXPOSE 9003
