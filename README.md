# dropwizard-microservice
Experiments with microservice architecture with dropwizard fullstack framework

Dropwizard is a sneaky way of making fast Java web applications.

Dropwizard lets you create lean and focused production ready reusable web applications.

It spins up an incredibly tuned HTTP server that uses the Jetty HTTP library.

It allows you to write clean, testable classes which gracefully map HTTP requests to simple Java objects using Jersy.
jakcson for json . In addition to being lightning fast, it has a sophisticated object mapper, allowing you to export your domain models directly.


Advantages of Dropwizard based services are as follows

Running your application as a simple process eliminates a number of unsavory aspects of Java in production (no PermGen issues, no application server configuration and maintenance, no arcane deployment tools, no class loader troubles, no hidden application logs, no trying to tune a single garbage collector to work with multiple application workloads) and allows you to use all of the existing Unix process management tools instead.

### References
http://www.dropwizard.io/0.9.2/docs/getting-started.html
