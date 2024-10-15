FROM openjdk:11.0.2-jre-slim

EXPOSE 8080

WORKDIR /app

COPY *.jar /app/app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]

# docker build -t tituschewxj/order-service:1.0.0 ./order-service