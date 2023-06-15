## 02-06-2023

### Problems microservices solving

- Most powerful benefits of microservices is how they force you to break your problems down into buildable pieces

- Makes the code more maintainable and testable (code is broken based on the functionality and makes it simple to maintain as they are broken and easy to hold context of small pieces)

- They give better scalability (in case of high traffic, rather than up scaling whole monolith we can now simply upscale the service where the traffic would be more)

- Allows developers to develop code in different language per service so they can choose a suitable language for that particular service's functionality

https://dzone.com/articles/what-problems-do-microservices-solve-2

### To refer on problems of using Microservices

https://www.bmc.com/blogs/microservices-challenges-when-to-avoid/

## 03-06-2023

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

ref:
https://microservices.io/patterns/monolithic.html

![huge_monolith_impacts](../Images/Impacts_of_large_monolithic_appl.png)

Microservices aren’t the best for on-premise

As a startup (not likely in this economy), you already are running against the clock, looking for a breakthrough before the next bad thing happens. You don’t need the scalability at this point (and probably not for a few years yet),

Microservices are only viable for mature products

Some companies which moved to microservices from monolithic

- Amazon :

  - Moving to microservices increased their scalability.
  - Allowed each team to handle their own service and processes.
  - Freed major code changes from not being stuck in the deployment pipeline for weeks.

- Bestbuy.com :

  10 on the Internet Retailer Top 500

  - Microservices made simple changes deploy faster.
  - To effectively handle peak level traffic.

- Coca Cola

  3,800 products worldwide and subsidiaries in all countries of the world

  - Migrating to microservices helped to connect entities in different continents and support their growth.

- eBay

  The company had 97 million active users and 62 billion gross merchandise volume.
  With typical traffic of 75 billion database calls, 4 billion page views and 250 billion search queries

  - Microservices made it easy to handle growing complexity of the codebase, improving developers’ productivity

- Etsy

  - To support the development of new features.
  - To allow continuous experimentation.

- Gilt.com

  A startup to a $1B fashion brand in the U.S

  - To have less dependencies between teams.
  - Running initiatives in parallel.
  - Supporting multiple technologies and promoting ease of innovation.

- Uber

  - Scalability and continuous integration

- Groupon

  Simple website designed to show one deal per day in Chicago, now expanded in 48 countries.

  - Shorten the Time for Shipping New Features

- PayPal

  Had thousand VMs. Each VM produced a very low throughput resulting increase in latency in the end user experience was deteriorating.

  - Moved to microservices improved User Experience.

- Twitter

  Increased code base lead to all-or-nothing deployments and long build times.

  - Moved to microservices and started fixing, testing and deploying the bugs.

- KarmaWifi

  It became hard to track the interactions between components because everything got entangled.

  - Microservices adoption made it easy to add a functionality independent of other services.
