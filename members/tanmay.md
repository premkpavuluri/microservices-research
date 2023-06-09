## Some questions you can ask before going with microservices or monolith architecture :

- What are your scalability requirements?
  - Microservices are a good choice for businesses that need to be able to scale quickly and easily. Monoliths can be more difficult to scale, especially as they get larger.

- How complex is the application you're building?
  - Does it involve multiple interconnected modules or domains that could benefit from independent development and deployment?

- How quickly do you need to develop and deliver the application?
  - Would a microservices architecture help you accelerate development by enabling parallel work on different components?

- What is the size and expertise of your development team?
  - Do you have separate teams with specialized skills that can handle different components of a microservices architecture?

- What are your requirements and preferences regarding deployment environments and infrastructure management? 
  - Do you have the necessary infrastructure and tools in place to support a microservices architecture?

- What are your security requirements?
  - Microservices can be more secure than monoliths, because each service can be isolated from the others.

- What is your budget?
  - Microservices can be more expensive to develop and maintain than monoliths.

<br>

#### Here is a table that summarizes the benefits and drawbacks of microservices and monoliths:

| Feature | Microservice | Monolith |
| :--- | :--- | :--- |
| Scalability | Very scalable | Less scalable |
| Flexibility | Very flexible | Less flexible |
| Maintainability | Easier to maintain | More difficult to maintain |
| Complexity | More complex to develop and deploy | Less complex to develop and deploy |
| Cost | More expensive to develop and deploy | Less expensive to develop and deploy |
| Experience  | More experience required | Less experience required |

When choosing between microservices and monolithic architectures, we can consider these factors along with specific project requirements, team capabilities, and organizational context to make an informed decision.

<br>
<hr>
<br>

## Here are some of the problems with monolithic architecture :

Slower development speed –
- A large, monolithic application makes development more complex and slower. A small change to a monolithic application requires the redeployment of the entire
monolith.

Difficult to scale - 
- Monolithic applications can be difficult to scale, especially as they grow in size and complexity. This is because all of the components in a monolithic application
share the same resources, such as memory, CPU, and database.

Single point of failure - 
- A monolithic application has a single point of failure, meaning that if any one component fails, the entire application will fail. This can be a major problem for
applications that require high availability.

Barrier to technology adoption – 
- Any changes in the framework or language affects the entire application, making changes often expensive and time-consuming.

Lack of flexibility – 
- A monolith is constrained by the technologies already used in the monolith.

Costly to maintain -
- Monolithic applications can be costly to maintain, as any changes or updates must be made to the entire application. This can be a major problem for applications
that are constantly changing.

## Advantages of Microservice architecture :

- Highly agile - Any application that uses microservices is agile. Making changes to one microservice allows you to redeploy it without disrupting other components.
Also, you can add and test new technologies easily.

- Scalable Development – With microservices, different development teams can work on different services simultaneously, enabling faster development cycles. Teams can
be organized around specific business domains or functional areas, allowing for more focused development efforts and quicker time-to-market for new features.

- Continuous Delivery – Microservices architecture allows for continuous delivery because each service can be deployed independently, without affecting the other services. This means that developers can continuously deliver updates and improvements to the system without disrupting other services. This results in faster delivery times, improved system reliability, and increased customer satisfaction. 

- Highly maintainable and testable – Teams can experiment with new features and roll back if something doesn’t work. This makes it easier to update code and 
accelerates time-to-market for new features. Plus, it is easy to isolate and fix faults and bugs in individual services.

- Independently deployable – Microservices are self-contained, independent deployment module.

- Support multiple technology stacks - Different services can use different technology stacks and can be upgraded independently.

- Isolation of services - Any fault in a microservices application affects only a particular service and not the whole solution. Therefore, all the changes and 
experiments are implemented with lower risks and fewer errors.

Reference: https://www.atlassian.com/microservices/microservices-architecture/microservices-vs-monolith
           https://blog.dreamfactory.com/7-key-benefits-of-microservices/


## Why projects are sticking with Monolithic :
Here are some companies that were used monolithic architecture for long period:

- Spotify
- LinkedIn
- Twitter
- Salesforce
- Adobe
- SAP
- Oracle
- IBM
- Microsoft

These companies are all large and complex, and their monolithic architectures have served them well for many years. However, as their businesses grow and their needs change, they may change their architecture.

These companies have different reasons for sticking with monolithic architecture for a long period of time. Here are some potential reasons:

- Legacy Systems: Some of these companies have been around for several decades, and their software systems were initially built using monolithic architecture. Over time, these systems became deeply ingrained in the company's operations and changing to a new architecture would require significant effort and resources.

- Stability and Reliability: Monolithic architectures, despite their drawbacks, can be stable and reliable when properly implemented. These companies might prioritize the stability of their systems over the potential benefits of adopting a microservices or distributed architecture.

- Cost and Complexity: Transitioning from a monolithic architecture to a microservices or distributed architecture can be a complex and costly process. It often involves re-engineering or rewriting significant portions of the existing software systems. These companies might hesitate to undertake such a massive endeavor due to the associated risks and resource requirements.

- Interdependencies: Monolithic architectures often result in tight coupling between different components of the system. In some cases, the functionality of various parts might be tightly integrated, making it challenging to decouple and migrate to a more modular architecture.

-----------
Here are a few examples of companies that continue to stick with monolithic architecture along with some reasons behind their decisions:

- Netflix: A popular streaming platform.
  - Transitioning to a distributed architecture would require a massive overhaul of their existing system.
  - Their monolithic architecture allows for centralized control and easier management of their extensive content catalog.

- Shopify: An e-commerce platform.
  - Shopify's monolithic architecture allows for faster feature development, deployment and maintenance.

- LinkedIn: The professional networking platform.
  - LinkedIn's monolithic architecture allows for rapid feature development and deployment, which is crucial in the fast-paced social media landscape. 
  - Their architecture provides centralized control and enables efficient data access across various features of the platform.

- Salesforce: A leading customer relationship management (CRM) platform. 
  - The reason behind this choice is the need for strong data consistency and security. 
  - Their monolithic architecture ensures better performance efficiency.

Now, there is a exceptional case where some companies realized that monolithic architecture is suitable based on their needs.
One current example of a company that has transitioned from microservices to a monolithic architecture is **Amazon Prime Video**.
- Moving to monolithic architecture reduce their infrastructure cost by 90%. It's also increased their scaling capabilities.
- Better customer experience due to faster processing of defunct videos.