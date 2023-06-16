# 29-05-2023

# 12-06-2023

## ARCHITECTURES

The increasing business complexity and demand for highly scalable applications have brought a paradigm shift in how software applications are engineered. In the past few years, different software architectures are adopted by developers to reduce code complexity, improve fault isolation, and minimize time-to-market.
Software architecture defines and structures a solution in a way that it meets all the technical, operational and business requirements. It is a foundation for the attributes of an application, its elements, relationships, and properties, which ultimately impacts its scalability and performance.

Two of the popular software architecture approaches that developers prefer are:
- Monolithic architecture
- Microservices architecture

Now let see those architecture with an example,

The demand of online shopping in increasing rapidly. People are prefer to buy products virtually rather than going to the market. On Demand Ecommerce App Development companies develop many ecommerce mobile apps that help users to buy anything they want without any hassle. 

  Let’s imagine that you are building an e-commerce application that takes orders from customers, verifies inventory and available credit, and ships them. The application consists of several components including the StoreFrontUI, which implements the user interface, along with some backend services for checking credit, maintaining inventory and shipping orders. <br>
  ### Sample Illustration of Monolith architecture of E-Commerce website

  ![Monolithic Architectures](../Images/monolithic_architecture.png)

  The application is deployed as a single monolithic application. A web application consists of a single file that runs on a server. A Rails application consists of a single directory hierarchy deployed using either, for example, Phusion Passenger on Apache/Nginx or JRuby on Tomcat. You can run multiple instances of the application behind a load balancer in order to scale and improve availability.
  
  - All operations can be implemented as an ACID transaction since there’s a single database
  - There’s no runtime coupling since there’s a single component
  - There’s no design-time coupling between multiple components

  ### Sample Illustration of Micro-services architecture of E-Commerce website

  ![Micro-service Architectures](../Images/micro_service_architecture.png)

  The above architecture consist of a User interface(Web and Mobile), Routing layer(API gateway),  Serveral services that provides specific e-commerce functionalities(Account service, Inventory service, Shipping services and others) and Data base for each service for data storage and retrieval.

  - each service consists of a small number of subdomains 
  - subdomains can be segregated by their characteristics into separate services in order to improve scalability, availabilty and security.

# 13-06-2023

## Disadvantages of Micro-service architecture

- Development sprawl : Microservices add more complexity compared to a monolith architecture, since there are more services in more places created by multiple teams. If development sprawl isn’t properly managed, it results in slower development speed and poor operational performance.

- Exponential infrastructure costs: Each new microservice can have its own cost for test suite, deployment playbooks, hosting infrastructure, monitoring tools, and more.

- Added organizational overhead: Teams need to add another level of communication and collaboration to coordinate updates and interfaces.

- Debugging challenges: Each microservice has its own set of logs, which makes debugging more complicated. Plus, a single business process can run across multiple machines, further complicating debugging.

- Lack of standardization: Without a common platform, there can be a proliferation of languages, logging standards, and monitoring.

- Lack of clear ownership: As more services are introduced, so are the number of teams running those services. Over time it becomes difficult to know the available services a team can leverage and who to contact for support.

- Version control, updations: As more services are introduced, it's hard to maintain the versions between services. Updation of one service make incompatible with other services.

- Need a have Holistic view of system: There needs to be person which keeps track of holistic view of whole system. The understanding needs updated as well.

- Hard to onboard: It's hard to onboard new people in to the system. Lot to catch-up on, Needs a person to onboard, etc.

- Forced to use orchestration tools: Since all the services need to bring together to run entire application, this will force to use orchestration tools like: docker, kubernetes ,..etc.

- Hidden contracts: The contract of each services are hard to track, chaining of one service contract makes effect on the dependent services.

Reference: https://www.atlassian.com/microservices/microservices-architecture/microservices-vs-monolith
