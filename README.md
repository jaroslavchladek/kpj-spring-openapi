# KPJ Spring + OpenAPI

One of examples for the students of Inventi Java Academy.

- `api` module contains the OpenAPI document we created during the lecture,
- `device-service` contains the service implementing the API.

## Requirements

- Java 17+
- Maven 3.6.0+

## How to

- First, you need to push the `api` module to your local Maven repository: `cd api && mvn install`
- Then, you can actually build the service: `cd device-service && mvn compile`
- To run the example, you can run the service via the IDE of your choice or with `cd device-service && mvn spring-boot:run`
  - After that, your service is available on `http://localhost:8082`
  - [Try it!](http://localhost:8082/devices)
- You can continue and implement the methods in `DeviceRestController.java`
- Try to change the OpenAPI document, too - and implement APIs of your own.