Microservices, also known as the microservice architecture, are an architectural style which structures an application as a loosely coupled collection of smaller applications. The microservice architecture allows for the rapid and reliable 
delivery of large, complex applications. Some of the most common features for a microservice are:

- It is maintainable and testable
- It is loosely coupled with other parts of the application
- It  can deployed by itself
- It is organized around business capabilities
- It is often owned by a small team.

In this project, developed a number of small, self-contained, loosely coupled microservices that will communicate with one another and a simple 
front-end application with a REST API, with RPC, over gRPC, and by sending and consuming messages using AMQP, the Advanced Message Queuing Protocol. 
The microservices includes the following functionality:

- A Front End service, that just displays web pages;
- An Authentication service, with a Postgres database;
- A Logging service, with a MongoDB database;
- A Listener service, which receives messages from RabbitMQ and acts upon them;
- A Broker service, which is an optional single point of entry into the microservice cluster;
- A Mail service, which takes a JSON payload, converts into a formatted email, and send it out.

Deploy distributed application to a Docker Swarm and Kubernetes, and scale up and down, as necessary, and to update individual microservices with little 
or no downtime.