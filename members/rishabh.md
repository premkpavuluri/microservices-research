## 01/06/2023

#### Problems Microservices Solve

the microservice architectural style is an approach to developing a single application as a suite of small services, each running in its own process and communicating with lightweight mechanisms, often an HTTP resource API. These services are built around business capabilities and independently deployable by fully automated deployment machinery.
<byline> - Martin Fowler</byline>

- Allow skill set felxibility (Everyone developing the app doesn't need to be proficient on a single tech stack)
- Developer efficiency (Faster Builds, less commit issues, smaller more managable code base )
- Easy less risky deployment (Less chance of breaking the whole application with a single deployment)

- Managable life cycle (Easier to switch to a better technology)

https://daedtech.com/what-problems-do-microservices-solve/#:~:text=With%20microservices%2C%20you%20get%20true,some%20enormous%20windfalls%20in%20productivity.

### great for getting examples of big companies using mciroservice arcitechture and the problem they solve for them

https://medium.com/containerum/10-tech-challenges-that-are-solved-by-microservices-d91adeecb2e7

### What is microservice architecture

an architecture that structures the application as a set of independently deployable, loosely coupled, components, a.k.a. services. Each service consists of one or more subdomains.

Some operations will be local (implemented by a single service), while others will be distributed across multiple services. A distributed operation is implemented using either synchronously using a protocol such as HTTP/REST or asynchronously using a message broker, such as Apache Kafka.

#### Basic features of Microservice architecture

- simple services dealing with one or more subdomains of the application
- team autonomy allows people with different experiences to develop application
- fast deployment (Independent microservice should not take long time to deploy)
- segregation based on characteristic such as cpu, gpu consumption scalability
- design should allow most of the distributed operations to efficient
- it should allow transactions to be ACID not BASE
- loose run time coupling (one service should not be dependent on availability of another service)
- loose design time coupling (packaging tightly coupled services together)

refs:
https://microservices.io/patterns/microservices.html

### Disadvantages of microservice

- Operations can't be implemented as an ACID transaction since there are multiple databases
- Some distributed operations might be hard to follow and debug
- Distributed operations might be tightly coupled which means that one microservice is heavily dependent on other
- Risk of tight design-time coupling between services, which requires time consuming lockstep changes
- It's hard to deploy prodcut wide updates (multiple microservices need to deployed at once)
- Hard to perform end-to-end tests with distributed microservice architecture.

reffs:
atlassian.com/microservices/microservices-architecture/microservices-vs-monolith
https://microservices.io/patterns/microservices.html

### What are monolithic applications

- An architecture that structures the application as a single deployable and executable component.The component contains all of the application’s subdomains. Since there’s a single component, all operations are local.

### Advantages and Disadvantages of Microservices Architecture

- Scalability :- Scalability is one of the most significant benefits of microservices.In a microservices application each service has its dedicated resources. So we can scale up only the required services. This improved scalability helps prevent outages and ensures that users always have a positive experience. It also helps to bring the cost down as you don't need to scale everything if one component is getting high traffic.

- Fault Isolation :- With a microservices architecture, the failure of one service is less likely to negatively impact other parts of the application because each microservice runs autonomously from the others.

- Language and Technology Agnostic :- When creating a microservices-based application, developers can connect microservices programmed in any language. They can also connect microservices running on any platform. This offers more flexibility to use the programming languages and technologies that best fit the project’s needs and your team’s skill sets. By becoming programming language agnostic, you can quickly adopt new technologies as they emerge and evolve. You’re no longer tethered to a single technology stack because you can use the best tool for each job.

- Faster Time to Market :- The pluggability of a microservices application architecture allows for easier, faster application development and upgrades. Developers can quickly build or change a microservice, then plug it into the architecture with less risk of coding conflicts and service outages. Moreover, due to the independence of each microservice, teams don’t have to worry about coding conflicts, and they don’t have to wait for slower-moving projects before launching their part of the application.

refs:

https://blog.dreamfactory.com/7-key-benefits-of-microservices/
