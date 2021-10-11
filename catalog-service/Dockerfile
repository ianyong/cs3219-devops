# To build this image, run:
# docker build -t cs3219/catalog-service:1.0.0 ./catalog-service

FROM openjdk:11.0.2-jre-slim

ENV APP_ROOT /service

RUN mkdir --parents $APP_ROOT
WORKDIR $APP_ROOT
COPY catalog-service-0.0.1-SNAPSHOT.jar .

EXPOSE 8080

CMD ["java", "-jar", "catalog-service-0.0.1-SNAPSHOT.jar"]
