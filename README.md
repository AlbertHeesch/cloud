## About
Welcome!  
The project you are looking at is a configuration server.

##Microservices & Front End
In order to run my application properly please use these projects:
- Discovery - https://github.com/AlbertHeesch/discovery,
- Gateway - https://github.com/AlbertHeesch/gateway,
- Main Back End - https://github.com/AlbertHeesch/DentClinicApp,
- Rates Back End - https://github.com/AlbertHeesch/DentClinicAppRates,
- Front End - https://github.com/AlbertHeesch/DentClinicAppView,
- Integration Test Suite - https://github.com/AlbertHeesch/DentClinicAppTesting.

## Requirements:

Java 11

Gradle

## How to run
Set `spring.cloud.config.server.native.searchLocations` path to `application-config` file (by default in project root) in `application.properties`.

Make sure that your localhost: 8080, 8081, 8082, 8083, 8084 and 8085 ports are available.

Build your gradle with `gradlew build` in terminal.

Run the projects in order:
- Configuration server,
- Discovery,
- Gateway,
- DentAppClinic & DentAppClinicRates,
- DentAppClinicView.

Now you can check http://localhost:8082 to see if all projects are registered in discovery.

Enter the http://localhost:8085/home page in your browser.