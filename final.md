# When And When Not To Choose Microservice Architecture.

## Index

1. What is microservices architecture?
2. What is monolithic architecture?
3. Architectural diagrams for microservice and monolithic architectures.
4. Advantages and Disadvantages of Microservice.
5. Advantages and Disadvantages of Monolithic.
6. Tabular difference of monolithic and microservices.
7. Why projects are moving towards microservices.
8. Why projects are sticking with monolithic.
9. What questions to ask to decide if someone needs microservices or not.
10. What is the conclusion of our research.
11. References.

## 1. What is microservice architecture

An architecture that structures the application as a set of independently deployable, loosely coupled, components, a.k.a. services. Each service consists of one or more subdomains.

Some operations will be local (implemented by a single service), while others will be distributed across multiple services. A distributed operation is implemented using either synchronously using a protocol such as HTTP/REST or asynchronously using a message broker, such as Apache Kafka.

### Basic features of Microservice architecture

- Simple services dealing with one or more subdomains of the application.
- Team autonomy allows people with different experiences to develop application.
- Fast deployment (Independent microservice should not take long time to deploy).
- Segregation based on characteristic such as cpu, gpu consumption scalability
- Design should allow most of the distributed operations to efficient.
- It should allow transactions to be ACID not BASE.
- Loose run time coupling (one service should not be dependent on availability of another service).
- Loose design time coupling (packaging tightly coupled services together).

## 2. What are monolithic applications

An architecture that structures the application as a single deployable and executable component.The component contains all of the application’s subdomains. Since there’s a single component, all operations are local.

### Basic features of monolithic architecture

- The component contains all of the application’s subdomains.
- Since there’s a single component, all operations are local.
- Simple to develop (as designing/understanding this architecture doesn't take much time and helps for applications in starting stages of development).
- Testing is simple (as everything is at one place).
- Deployment of the whole application is done in case of changes.
- One has to run multiple instances of the application using load balancer in order to scale and improve availability of the application.
- All operations can be implemented as an ACID transaction since there’s a single database.
- There’s no runtime coupling and design-time coupling as there are no multiple components.

## 3. Architectural diagrams for microservice and monolithic architectures.

## 4. Advantages and Disadvantages of Microservice.

## 5. Advantages and Disadvantages of Monolithic.

## 6. Tabular difference of monolithic and microservices

## 7. Why projects moving towards microservices.

## 8. Why projects are sticking with monolithic.

## 9. What questions to ask to decide if someone needs microservices or not.

![flow_chart](Images/question-flow-chart.png)

## 10. Conclusion

## 11. References

### Section 1

- https://microservices.io/patterns/microservices.html

### Section 2

- https://microservices.io/patterns/monolithic.html
