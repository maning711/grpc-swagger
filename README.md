[![Build Status](https://travis-ci.com/grpc-swagger/grpc-swagger.svg?branch=master)](https://travis-ci.com/grpc-swagger/grpc-swagger)

[sonar](https://sonarcloud.io/dashboard?id=io.grpc%3Agrpc-swagger)

# run with Docker
```
mvn clean package
docker build -t grpc-swagger .
docker run -p 8080:8080 grpc-swagger
```