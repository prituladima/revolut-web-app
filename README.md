# Test task for revolut

While the code is surprisingly simple, under the hood this is using:
 - RESTEasy to expose the REST endpoints
 - Hibernate ORM with Panache to perform the CRUD operations on the database
 - A H2 database
 - ArC, the CDI inspired dependency injection tool with zero overhead
 - The high performance Agroal connection pool
 - Infinispan based caching
 - All safely coordinated by the Narayana Transaction Manager
 - Servlet container is embedded

## Requirements

To compile and run this demo you will need:
- Java `8+`
- Apache Maven `3.5.3+`

## Building and running the demo

Linux
> run.sh

Windows
> run.cmd

## Postman collection

> Revolut.postman_collection.json