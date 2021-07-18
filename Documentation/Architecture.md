
# [Zowe](https://www.zowe.org/) Explorer Extension Template Architecture

![alt text](Architecture.png)

## Components

  * ["Zowe Sample API service"](https://github.com/zowe/sample-spring-boot-api-service/blob/master/zowe-rest-api-sample-spring/README.md)  - web server
  * "Zowe CLI plugin [(cURL)](https://curl.se/)" will use cURL to get data from the "Zowe sample REST API"
  * "VS Code extension" will be build on the developed "zowe CLI plugin [(cURL)](https://curl.se/)"
  * The "User" will interact with all these components through the generated "VS Code Extension"

## Technologies Used

* Typescript
* [Node.js](https://nodejs.org)
