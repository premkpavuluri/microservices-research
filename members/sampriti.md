# 29-05-2023
 -----

# 07-06-2023

Deploy microservices:
https://semaphoreci.com/blog/deploy-microservices

# 12-06-2023
8 stages for migrating existing applications to microservices
- https://insights.sei.cmu.edu/blog/8-steps-for-migrating-existing-applications-to-microservices/

# 15-06-2023

# Disadvantages of Monolithic Architecture :

## Slow speed of development:
   The simplest disadvantage relates to CI/CD pipeline. Imagine the monolith that contains a lot of services. Each service in this monolith is covered with tests that are executed for each Pull Request. Even for a small change in a source code you should wait a lot of time for your pipeline to succeed. 
   And what happens when the pipeline fails for some reason? You wait again. All services are located in a single place. The size of the team is big. What happens when your colleague merges their changes? You rebase/merge and wait again.

## High code coupling:
   Of course you can keep a clear service structure inside your repository. However, as practice shows, eventually you will end up with a spagetti code in at least a few places. As a result, the system becomes harder to understand especially for new team members.

## Code ownership cannot be used:
   The system is growing. The logical step is to split responsibilities between several teams. E.g. one team can work on Flight Service, another – for Billing Service. However, there are no boundaries between those services. One team can affect another.

## Testing becomes harder:
   Even a small change can negatively affect the system. As a result, the regression for full monolithic service is required.

## Performance issues:
   Potentially, you can scale the whole monolithic service in cases of performance issues. But what to do with the database? The single database is used for all services. You can start to optimize your database queries or use read replicas. However, there is a limit to this type of optimizations.

## The cost of infrastructure:
   In cases of performance issues, you should scale the whole monolithic service. It brings additional cost for application operability.

## Legacy technologies:
   Imagine that you have the application written on Java 8. How much time is it required to migrate the whole monolith with multiple services underneath to Java 11? What to do with the tasks that are required to bring new functionality? It can be the case that the application will never be migrated.
  
## Lack of flexibility:
   A monolith is constrained by the technologies already used in the monolith. You cannot use other tools even if they are better for the problem at hand.

## Reliability:
   If there’s an error in any module, it could affect the entire application’s availability.

