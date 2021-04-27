# Learning-gRPC
This project helps to understand gRPC communication mechanism with Java examples.

Modern day applications are designed with microservices architecture. Microservices need to communicate between them to perfom an activity. The widely used communication mechanism is REST. In this approach, we model our application (or) service as a collection of resources that can be accessed and have their state changed via network calls. These network calls runs over HTTP Protocol. 

Developing a gRPC application
1. Define a service interface. The language to be used is called as Interface Definition Language (IDL).
2. This definiation contains information on how the service(method) will be, i.e. Payload, request, response. 
3. Using protoc, generate server side code and client side stubs. 
