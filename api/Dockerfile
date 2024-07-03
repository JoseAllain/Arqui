FROM eclipse-temurin:17-jdk-alpine
WORKDIR /app
COPY target/api.jar api.jar
EXPOSE 8080
CMD ["java","-jar","api.jar"]