### What is microservice architecture

An architecture that structures the application as a set of independently deployable, loosely coupled, components, a.k.a. services. Each service consists of one or more subdomains.

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

### What are monolithic applications

- An architecture that structures the application as a single deployable and executable component.

#### Basic features of monolithic architecture

- The component contains all of the application’s subdomains.
- Since there’s a single component, all operations are local.
- Simple to develop (as designing/understanding this architecture doesn't take much time and helps for applications in starting stages of development)
- Testing is simple (as everything is at one place)
- Deployment of the whole application is done in case of changes.
- One has to run multiple instances of the application using load balancer in order to scale and improve availability of the application.
- All operations can be implemented as an ACID transaction since there’s a single database
- There’s no runtime coupling and design-time coupling as there are no multiple components
