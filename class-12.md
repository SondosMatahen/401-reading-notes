# Class-12
## OAuth

#### How does OAuth work?
Through a series of “handshakes”, an application such as an Express Web Server asks the user if it’s ok to login as them at some remote service, and then begins the process of authentication and access.

  1. Application spawns the “Login Using xxx” window, asking for specific permissions
  2. User Agrees to allow this to happen
  3. Remote service (i.e. Google) contacts the application with a one-time-use Code
  4. The application calls back to a special address on the remote service to exchange that Code for a Token
  5. Once the token has been granted, the application will then be able to contact the remote service, using that Token to access information on behalf of the user