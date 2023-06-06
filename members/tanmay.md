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