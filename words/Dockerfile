FROM maven:3.6.3-jdk-8 AS words

COPY . .

RUN mvn dependency:resolve

RUN mvn package

FROM openjdk:8-jre-alpine

COPY --from=words target/ .

CMD ["java", "-Xmx8m", "-Xms8m", "-jar", "words.jar"]

EXPOSE 8080