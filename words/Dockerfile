FROM maven:3.6.3-jdk-8

COPY . .

RUN mvn dependency:resolve

RUN mvn package