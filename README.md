# What is This?
Simple Spring boot microservice that returns json limits from a Spring Cloud Config Server properties. Yes, that makes this limits-service app and spring cloud client. Complimentary of in28Minutes
Spring Boot Microservices Udemy Course


## How to Run Locally 
First, clone this other repo (https://github.com/Step-henC/spring-cloud-config-server-limits)[Spring Cloud Config Server] and follow instructions to get it running locally.

Did you follow the Spring Cloud Config Server instructions? Good. 

Next, clone this repo and run in the code editor of your choice. If using VS code, navigate to src/main/java/com/spring/cloud/rest/services/limitsservice/LimitsServiceApplication.java
and left click to choose option that says "run Java". Or open terminal and type "mvn spring-boot:run "
Should be running on port 8080. Navigate to "http://localhost:8080/limits to get limits value. 

To change limits value for dev and qa enviornments, navigate to src/main/resources/application.properties and change line 15 to read either dev or qa. 
Then, when you refresh your browser to http://localhost:8080/limits you will the values for ea environment.
