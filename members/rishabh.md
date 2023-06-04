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
