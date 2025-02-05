FROM openjdk:17-slim
RUN apt-get update && apt-get install -y curl
COPY ./app_config.jar app_config
EXPOSE 9000
CMD ["java", "-jar", "/app_config"]