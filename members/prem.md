# 29-05-2023

# 12-06-2023
 
## ARCHITECUTRES
- Microservices-Monolith architecture.<br>
  https://www.atlassian.com/microservices/microservices-architecture/microservices-vs-monolith

- Target: E-commerce domain. <br>
  Let’s imagine that you are building an e-commerce application that takes orders from customers, verifies inventory and available credit, and ships them. The application consists of several components including the StoreFrontUI, which implements the user interface, along with some backend services for checking credit, maintaining inventory and shipping orders. <br> 
  Sample Illustration of Micro-service and Monolith architecture of E-Commerce website

  ![Architectures](../Images/architectures.png)


# 13-06-2023

## Disadvantages of Micro-service architecture

- Development sprawl : Microservices add more complexity compared to a monolith architecture, since there are more services in more places created by multiple teams. If development sprawl isn’t properly managed, it results in slower development speed and poor operational performance. 

- Exponential infrastructure costs:  Each new microservice can have its own cost for test suite, deployment playbooks, hosting infrastructure, monitoring tools, and more.

- Added organizational overhead: Teams need to add another level of communication and collaboration to coordinate updates and interfaces. 

- Debugging challenges: Each microservice has its own set of logs, which makes debugging more complicated. Plus, a single business process can run across multiple machines, further complicating debugging. 

- Lack of standardization: Without a common platform, there can be a proliferation of languages, logging standards, and monitoring. 

- Lack of clear ownership: As more services are introduced, so are the number of teams running those services. Over time it becomes difficult to know the available services a team can leverage and who to contact for support.

- Version control, updations

- Need a have Holistic view of system

- Hard to onboard

- Forced to use orchestration tools

- Hidden contracts

Reference: https://www.atlassian.com/microservices/microservices-architecture/microservices-vs-monolith
