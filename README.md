# Dropwizard Based Hello World Microservice

Experiments with microservice architecture with dropwizard fullstack framework.

- Dropwizard lets you easily create lean, focused, production ready, reusable, lightning fast Java web applications.
- It spins up an incredibly tuned HTTP server that uses the Jetty HTTP library.
- It allows you to write clean, testable classes which gracefully map HTTP requests to simple Java objects using Jersy.
- With use of Jackson it allows to export  domain models directly.

## Advantages of Running your application as a simple process using Dropwizard are as follows
- No PermGen issues
- No application server configuration and maintenance
- No arcane deployment tools
- No class loader troubles
- No hidden application logs
- No trying to tune a single garbage collector to work with multiple application workloads
- Allows you to use all of the existing Unix process management tools

### Running The Application

To test the example application run the following commands.

* To package the example run.

        mvn package

* To run the server run.

        java -jar target/dropwizard-microservice-1.0-SNAPSHOT.jar server hello-world.yml

* To hit the Hello World example (hit refresh a few times).

	http://localhost:8080/hello-world


### References
http://www.dropwizard.io/0.9.2/docs/getting-started.html
https://jersey.java.net/
http://wiki.fasterxml.com/JacksonHome
