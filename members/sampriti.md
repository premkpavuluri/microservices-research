# 29-05-2023

---

# 07-06-2023

Deploy microservices:
https://semaphoreci.com/blog/deploy-microservices

# 12-06-2023

8 stages for migrating existing applications to microservices

- https://insights.sei.cmu.edu/blog/8-steps-for-migrating-existing-applications-to-microservices/

# 15-06-2023

# Disadvantages of Monolithic Architecture :

- Difficult to scale :- Monolithic applications can be difficult to scale, especially as they grow in size and complexity. This is because all of the components in a monolithic application share the same resources, such as memory, CPU, and local-storage. In monolithic architecture it is impossible to scale a single component on it's own. We are forced to allocate extra resources to the entire system.

- Single point of fragility :- A monolithic application has a single point of failure, meaning that if any one component fails, the entire application will fail. This can be a major problem for applications that require high availability.

- Barrier to technology adoption :- A monolith is constrained by the technologies already used in the monolith. You cannot easily introduce new tools even if they are better for the problem at hand. Adopting a newer technology into the system is also difficult and a lot of planning is required to incorporate new technologies.

- Slower Delivery :- Every feature takes a lot of time to deploy to production. For every change we have to deploy the entire application. If we want to deliver small features we still have to deploy the whole application. This makes the delivery slower and certainly doesn't help agility.

- Lower Data Security :- Since there's only a single database for the entire application it opens more windows for data corruption as all pieces of code have same access to the database this allows them to change data that might not be related to them. Developers need to follow strict coding practices to make sure this doesn't happen.

#### references:

https://datamify.com/architecture/how-to-understand-monolithic-architecture/

https://www.openlegacy.com/blog/monolithic-application

https://semaphoreci.com/blog/2017/03/21/cracking-monolith-forces-that-call-for-microservices.html


## 21-06-2023

## What questions to ask to decide if someone needs microservices or not - [Paragraph]

- When deciding whether someone needs microservices or not, there are several factors to consider as follows 
  * Understand the Application
  * Analyze Business Domain and Functionalities
  * Scalability and Performance Requirements
  * Team and Development Structure
  * Integration and External Services
  * Technology and Language Flexibility
  * Security and Compliance Requirements
  * Future Maintainability and Evolvability 

  Based on those factors there are some key questions to consider like, 

  - Is the application expected to scale significantly in terms of functionality, traffic, or user base?
  - Do you anticipate the need for independent deployment and scalability of different components or services within the application?
  - Is the application currently experiencing or likely to experience challenges with monolithic architecture, such as tight coupling, difficulties in maintaining or updating specific features, or scalability issues?
  - Are there distinct business domains or functionalities within the application that can be logically separated?
  - Do you require the ability to adopt different technologies or programming languages for different components of the application?
  - Are there specific security or compliance requirements that could be better addressed through isolated and independently secured microservices?
  - Do you expect frequent changes or updates in specific parts of the application while others remain relatively stable?
  - Is there a need for fault isolation, so that failures in one component or service do not bring down the entire application?
  - Do you have the necessary infrastructure and operational capabilities to manage and orchestrate a distributed system of microservices? etc.

  Based on a project, is it already running or have to create from scratch we can ask those questions consecutively as picture -

  ![flow_chart](../Images/question-flow-chart.png)

  By discussing these questions with the relevant stakeholders and considering their responses, you can gain a better understanding of whether microservices would be a suitable architectural choice for the given scenario. It's important to note that the decision should be made based on the specific requirements and constraints of the project at hand, as microservices come with additional complexity and operational overhead compared to a monolithic architecture.

 ### References:
     https://chat.openai.com/
     https://medium.com/@daniel.dan/why-do-you-need-to-use-microservices-architecture-for-your-project-b0134cf61ceb
   