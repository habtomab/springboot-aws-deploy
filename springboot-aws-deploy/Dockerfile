FROM eclipse-temurin:21-jdk-alpine
RUN apk add --no-cache curl
VOLUME /temp
EXPOSE 8080
ADD target/springboot-aws-deploy-service.jar springboot-aws-deploy-service.jar
ENTRYPOINT ["java","-jar","springboot-aws-deploy-service.jar"]