# Java Microservices

This project possess a collection of Java microservices to create a complete environment with different Spring Cloud technologies integrated with each other.

## Objective

The aim of this project is to create a business case of payments service through the use of microservices

## Technologies

I use technologies like Spring Cloud Config Server to load files and properties stored in a Github repository, 
then I use a Cloud Management Properties to select the specific configuration and properties that will be shared with other microservices (in this case I share datasource properties),
then I use an Eureka Server to manage and centralize the different instances of microservices registered in this server,
as well, I use Spring Cloud Gateway and Spring Cloud Security to control the income and outcome request to the microservices, and the user authentication.
Finally, we integrated with Zipkin to trace the different request sent and received among microservices, allow me to have a control and observability of my microservice application.

For the side of the web integration, I use a web SPA project developed in Angular, it's simple, but useful to interact with the different JAVA microservices.

In the future, I would like to resolve some problems related with the migration of the new version of Spring Boot 3.0 and Spring Cloud.


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
