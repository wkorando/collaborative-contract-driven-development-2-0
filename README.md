# Collaborative Contract Driven Development

Code for presentation "Collaborative Contract Driven Development"

This articles provides a good overview of this area: [Spring Cloud Contract in a Polyglot World](https://spring.io/blog/2018/02/13/spring-cloud-contract-in-a-polyglot-world)

This code project takes more of a consumer driven contract approach to using Spring Cloud Contract in a polyglot world. The producer, "Produce Service" is a Spring Boot application, the front-end service is a Javascript (to be added later). The developer, hypothetically writing the produce client, likely wouldn't have much knowledge around Java development and/or build tools for running Java application installed on their system. Spring Cloud Contract provides docker images that encapsulate all the Spring Cloud Contract logic allowing a Javascript, and/or non-Java developer to write contracts (in YAML) and test those contracts work, and then run a stub server which can serve as mock representation of the real Produce Service API. 

Contracts located in repo: [Produce Contracts](https://github.com/wkorando/produce-contracts)

Client located in repo: [Produce Client](https://github.com/wkorando/produce-client)

Service located in repo: [Produce Service](https://github.com/wkorando/produce-service)
