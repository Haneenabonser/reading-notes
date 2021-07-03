## Authentication
### Review, Research, and Discussion

- Explain what a “Singleton” is (in Computer Science terms)
    - In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.
- Explain how the Singleton pattern can be used with Node modules, specifically with classes?
    - It is used where only a single instance of a class is required to control the action throughout the execution. A singleton class shouldn't have multiple instances in any case and at any cost. Singleton classes are used for logging, driver objects, caching and thread pool, database connections.
- If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?


## Vocabulary Terms
- Router Middleware: Router is one of the middlewares, what it does actualy is to take the original request, and forward it to a sub handler according to the path example : "/home" for a GET request is mapped to function getHome that handle it and eventually send a response to the client on the behalf of the original handler. 
- Dynamic Module Loading: is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.
- Singleton Pattern: is a creational design pattern, which ensures that only one object of its kind exists and provides a single point of access to it for any other code.
- CRUD -> REST Method Matches: 
> C create -> POST                                   
> R read -> GET                          
> U update -> PUT/PATCH                                      
> D delete -> DELETE                       
- Mock Testing: is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones.

## Preview
- Which 3 things had you heard about previously and now have better clarity on?
    - Authentication.
    - HTTP header.
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - node.bcrypt.js // Securing Passwords with Bcrypt Hashing Function.
- What are you most excited about trying to implement or see how it works?
    - TLS Client Authentication.
