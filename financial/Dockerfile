
FROM maven:3.9.9-eclipse-temurin-17 AS build 

WORKDIR /finance-api

COPY . . 

RUN mvn clean package -DskipTests
# Ver de mudar no runtime inves de usar JDK trocar para JRE 
FROM eclipse-temurin:17-jdk 

WORKDIR /finance-api

COPY --from=build /finance-api/target/*.jar finance-api.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar","finance-api"]