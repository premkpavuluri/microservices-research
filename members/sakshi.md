## Advantages of monolithic

- Simple to develop and deploy - In initial stage it is easy to develop because all the components of the application are developed together. So, developer don't need to deal with complex inter-communication between systems or manage multiple code-bases. Since all the code is at one place we only need to deploy a single application which makes it really easy to deploy.

- Easy to test and debug - Testing a monolith application end to end is very easy since a single process is responsible for completion of a request. As all the operations are taking place in a single process it makes debugging a lot easier since we don't need to go through logs of multiple processes to identify a bug.

- Easy to onboard new member - As all the code is at a single place and is written in one language. It's easy for a new team member to get a functional flow of the entire system.

- Low cost and time for initial setup - As there is single application we need to setup only one service so it won't take much time for initial setup as compare to a distributed system. Since there is single process we can share the resources so it won't cost much.

- Cross-cutting concerns and customizations - Cross cutting concerns refers to aspect of software development that affects multiple parts of an application such as logging mechanism, security, exception handling, setup for database connection pools. We only need to set these up once.

#### added optional point

- Easy to provide security for whole app - As there's a single point entry to the application providing security at that point is much more easier than providing security at each service in microservices.

Reference - https://datamify.com/architecture/how-to-understand-monolithic-architecture/
