
# [Zowe](https://www.zowe.org/) Explorer Extension Template Architecture

![alt text](Architecture.png)

## Components

  * ["Zowe Sample API service"](https://github.com/zowe/sample-spring-boot-api-service/blob/master/zowe-rest-api-sample-spring/README.md)  - web service
  * "Zowe CLI plug-in " will use [cURL](https://curl.se/) to connect to the ["Zowe Sample API service"](https://github.com/zowe/sample-spring-boot-api-service/blob/master/zowe-rest-api-sample-spring/README.md), which will then get data from the "Zowe sample REST API" and return it in JSON format
  * "VS Code extension" will be build on the developed "zowe CLI plug-in"
  * The "User" will interact with all these components through the generated "VS Code Extension"

## Technologies Used

* Typescript
* [Node.js](https://nodejs.org)
