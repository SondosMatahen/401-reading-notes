# Class-13
## OAuth

#### Bearer Authentication

Following a signin attempt, either using Basic Authentication (where your username and password are transmitted to a server) or OAuth (where there is a cumbersome handshaking/authorization process), your service is able to make a boolean decision as to the success of the attempt.

Assuming the signin was successful, we can assert that it would be both more efficient and secure if the server “just knew” that the client making subsequent requests was allowed to do so.

Rather than continually sending username+password over the internet, or undergoing the long OAuth process, we are able to use a secondary authentication method called “Bearer Token”

Bearer Tokens are encoded JSON objects that “bear” or “contain” enough information for the server to assert that any client request that presents a valid token must have originated from a client that has previously authenticated themselves using either Basic or OAuth. Upon receiving a Bearer Token from a client, the server can decode it, inspect the JSON object inside, look up the appropriate account, and re-authenticate the user in a single lookup.