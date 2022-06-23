 - **Integration testing**
   - Definition: Integration testing is the phase in software testing in which individual software modules are combined and tested as a group. Integration testing is conducted to evaluate the compliance of a system or component with specified functional requirements
   - Tech:
     - SpringBootTest to configure and up the Spring project to be tested 
     - MockMvc to emulate http requests
   - Location: https://github.com/gabrielsmenezes/backend-mediador-pedagogico/blob/3dc24d6ff51acb3b47db5dbc2438f4718431acd4/free-access/src/test/java/com/example/freeaccess/controller/ControllerTest.java
   - Context: In this class, I tested save, update and find feature from an application. To be a real integration test, we need to use real classes like @Services and @Repositories. Some of these features have restrictions as not null fields, so I also created tests to handle theses situations.

 - **Mock on tests**
   - Definition: XXX
   - Tech:
     - Mockito
   - Location: https://github.com/Pedagogical-Mediator/free-access/blob/master/src/test/java/com/example/freeaccess/controller/NoticeIntegrationTest.java
 
 - **Strategy Method**
   - Definition: Strategy is a behavioral design pattern that lets you define a family of algorithms, put each of them into a separate class, and make their objects interchangeable.
   - Tech: Java pure
   - Location: https://github.com/Pedagogical-Mediator/free-access/blob/2828304e61205d4481438f4b02f35e372c279acb/src/main/java/com/example/freeaccess/service/notice/SaveNotice.java#L33



Neste repositórios reuni os princiapis conceitos e principais tecnologias que utilizei em experiencias proficionais e em cursos da Alura. Abaixo listo uma a uma, explico brevemente e cito exemplos de onde foi utilizado:
- Spring Boot
   - Validation
- Spring Data
   - JPA
- Spring Cloud
   - Eureka
   - Config
- H2

Futuro
- Docker 
- JUnit
- BDD
   - Cucumber
- Design Patterns
- Circuit Breaker
- BulkHead
- Config Server
- Discovery Server or Registry Server or Eureka Server
- API Gateway
- DDD
- TDD
- Java Servlet
- SOLID
- Clean Architecture
