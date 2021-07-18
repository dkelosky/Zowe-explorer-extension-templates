
# [Zowe](https://www.zowe.org/) Explorer Extension Template Architecture

![alt text](Architecture.png)

## Components

  * ["Zowe Sample API service"](https://github.com/zowe/sample-spring-boot-api-service/blob/master/zowe-rest-api-sample-spring/README.md)  - web service
  * "Zowe cli plugin [(cURL)](https://curl.se/)" will curl the "Zowe sample REST API"
  * "Vs code extension" will be build on the developed "zowe cli plugin [(cURL)](https://curl.se/)"
  * The "User" will interact with all these components through the generated "vs code Extension"

## Technologies Used

* Typescript
* [Node.js](www.nodejs.org)
