# Data Transfer Objects

Right now, our web API exposes the database entities to the client. The client receives data that maps directly to your database tables. 

To accomplish this, you can define a data transfer object (DTO). A DTO is an object that defines how the data will be sent over the network. Let's see how that works with the Book entity.
# How to use Data Transfer Objects

A Data Transfer Object (commonly known as a DTO) is usually an instance of a POCO (plain old CLR object) class used as a container to encapsulate data and pass it from one layer of the application to another. You would typically find DTOs being used in the service layer to return data back to the presentation layer. The biggest advantage of using DTOs is decoupling clients from your internal data structures.

## Why use Data Transfer Objects (DTOs)?
When designing and developing an application, if you’re using models to pass data between the layers and sending data back to the presentation layer, then you’re exposing the internal data structures of your application. That’s a major design flaw in your application.
