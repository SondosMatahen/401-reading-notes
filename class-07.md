# Class-07
## Express

#### Express Routing
 - Event driven system
 - The Request Object
 - The Response Object

#### Express Middleware
  - A series of functions that the request “goes through”, each function receives request, response and next as parameters
  - Types of middleware:
    * Application
    * Route
  - Application Middleware: Error Handling, Bringing in other routes, Applies Defaults, JSON, Body and Form Parsing, Runs on every request.
  - Route Middleware: Dealing with specific things for a route.
  
#### Server Testing
  - Generally, avoid starting the actual server for testing, Instead, export your server as a module in a library, Then, you can use supertest to run your tests, This will hit your routes as though your server was running, without actually starting it That’s one less thing to go wrong (eliminate variables when testing!)
  - Why is this cool? We can 100% fake every call to the API. Again – you don’t want your tests of the web server to be dependent on the API running, so mock (fake) it, so that you are testing only the interface to the API, not the actual data.
  - You test the data/veracity of the API when you write your API tests, not web server tests…

#### Test Pyramid
  - Server Testing crosses boundaries
    * Units: Server Internal Functions
      - Mock any integrations (like data fetching)
    * Integration: How it connects to other services
      - Really connect to other services (hard dependencies)
    * Acceptance
      - The server might be a dependency of some other test