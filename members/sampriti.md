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
