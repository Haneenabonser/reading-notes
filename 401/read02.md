## Express

- What’s the difference between PUT and PATCH?
    - In a PUT request, the enclosed entity is considered to be a modified version of the resource stored on the origin server, and the client is requesting that the stored version be replaced.
    - With PATCH, however, the enclosed entity contains a set of instructions describing how a resource currently residing on the origin server should be modified to produce a new version.

- Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
    - Mockable.io
    - Postman Mock Server
    - MockServer

- Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?
    - APIDoc.js : Node.js CLI module to generate the documentation, when you are developing an API and one or more developers (frontend, desktop, mobile, etc) will have to integrate their code with it, it’s very important to have it well documented so they know what and how they can use.
    - Swagger: is an Interface Description Language for describing RESTful APIs expressed using JSON. Swagger is used together with a set of open-source software tools to design, build, document, and use RESTful web services.

- Compare and contrast SOAP and ReST
    - SOAP stands for Simple Object Access Protocol || REST stands for Representational State Transfer.
    - SOAP was designed with a specification. It includes a WSDL file which has the required information on what the web service does in addition to the location of the web service || REST is an Architectural style in which a web service can only be treated as a RESTful service.
    - SOAP cannot make use of REST since SOAP is a protocol and REST is an architectural pattern || REST can make use of SOAP as the underlying protocol for web services, because in the end it is just an architectural pattern.





## Vocabularies 
- Web Server : is a computer that runs websites,it is software and hardware that uses HTTP (Hypertext Transfer Protocol) and other protocols to respond to client requests made over the World Wide Web. 
- Express: is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.
- Routing: is the process of selecting a path for traffic in a network or between or across multiple networks.
- WRRC: Whole Request Response Cycle