# Class-11
## Authentication

#### User Modeling
  - Modern web applications need to model sensitive information about their users. When users provides an applications with sensitive information, they are trusting that it will not be leaked are misused.
  - Some information, like emails, user names, and addresses can be stored in plain text, as long as the database is password protected and/or behind a firewall.
  - Other information, like a users password, should be **encrypted** using a hashing algorithm before it is ever stored. this prevents anyone (including developers with database permissions) from ever getting access to their password.

  - User models that have sensitive data that should NEVER be sent to client applications. If your application requires that users be able to read each others personal information, create a **second Profile model** to hold that data and strictly limit access to the Profile model. 
  - Safely using a second model will ensure that no users will accidentally (or maliciously) get access to sensitive information.

#### Cryptography
  - Cryptography is the science which studies methods for encoding messages so that they can be read only by a person who knows the secret information required for decoding, called the key; it includes cryptanalysis, the science of decoding encrypted messages without possessing the proper key, and has several other branches.


#### Hash Algorithms
  - A Cryptographic Hash Algorithm takes a piece of data and produces a hash that is deliberately difficult to reverse. If identical data is passed into the algorithm the same hash will always be produced.
  - Hash algorithms are often used for checking the integrity of data.

#### Cypher Algorithms
  - A Cryptographic Cypher Algorithm takes a piece of data and a key and produces encrypted data. Later the encrypted data can be reversed into the original data by decrypting it using the same key.
