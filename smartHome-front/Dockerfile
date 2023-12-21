FROM maven:3.8.4-openjdk-17 AS builder
  WORKDIR /app
COPY ./src ./src
COPY ./pom.xml .
RUN mvn clean package
