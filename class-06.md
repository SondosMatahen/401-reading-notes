# Class-06
## HTTP and REST

#### HTTP

- **The Hyper Text Transfer Protocol**: is a stateless request-response application layer protocol.
- HTTP is **used to** build distributed, collaborative, hypermedia information systems.
- HTTP is the foundation for the world wide web. Applications built using HTTP subscribe to the client-server computing model.
- **Server** In the client-server computing model it is a host designed to provide a service.
- **Clients** are hosts that make requests to that service.
- HTTP is often associated with serving .html files but is also used to transfer images, videos, .json, .xml, binary executables, and much more.

- HTTP methods :
  * **GET** : Retrieve a resource.
  * **HEAD** : Like GET but headers only.
  * **POST** : Create a resource.
  * **PUT** : Update a resource.
  * **DELETE** : Delete a resource.
  * **CONNECT** : Create TCP/IP tunnel.
  * **OPTIONS** : Returns supported methods for a URL.
  * **TRACE** : Echos retrieved request.
  * **PATCH** : Partial modification of resource.


#### REST
- REST is acronym for REpresentational State Transfer.
- In layman’s terms, is a means by which we can reference, manipulate, and transfer state. Rest uses a common set of methods (called “verbs”) to operate on the state of a resource (“noun”), generally **using HTTP as the transfer protocol**.

- A **“RESTful Endpoint”** is a URI that identifies the resource. When addressed with a proper method, you are able to effect state. In normal terms, this means “Performing CRUD operations over HTTP”.

- REST methods :
  * **GET** : Retrieve 1 or More Records.
  * **POST** : Create a new record.
  * **PUT** : Update a record through replacement (Put it back).
  * **PATCH** : Update a record (just the parts that changed).
  * **DESTROY** : Remove a record.
