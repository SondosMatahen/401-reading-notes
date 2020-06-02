# Class-09
## API-server

#### Mongoose
- Mongoose is a schema driven ORM, which gives us the opportunity to provide structure to our Mongo documents. By default, Mongo (all NoSQL Databases, really) are not structured by default. Mongoose takes some of that pain away from us as developers and allows us to provide some level of rules and validation around our data models.

- With the addition of “Sub Documents”, Mongoose gives you the ability to take that a step further and use a schema to describe a deeper part of a data model. This can be useful when a document contains potentially a list of other documents.
  - For example, an online store likely has a collection of products. They probably also have a list of customers, each of which has placed orders which contain one or more products. When modeling the users collection, it would be nice to add orders as an array, and within the orders, and array of items … if you’ve previously modeled an item, you can re-use that schema within the orders section of a customer to keep the shape of that data the same.

- Note: Simply sharing a schema as a sub-document doesn’t bring in or connect the data, it simply uses the schema/rules. It’ll be up to you to manage the actual data.
