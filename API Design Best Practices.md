# API Design Best Practices

### What does REST stand for?
Representational State Transfer

### REST APIs are designed around a ***resources***.
### What is an identifier of a resource? Give an example.

 is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be: https://adventure-works.com/orders/1
 
### What are the most common HTTP verbs?
GET, POST, PUT, PATCH, and DELETE.

### What should the URIs be based on?
### Give an example of a good URI.
### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
 APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires, and its bad we should avoid

### What status code does a successful GET request return?
200

### What status code does an unsuccessful GET request return?
- 404 (Not Found)
- 204 (No Content)

### What status code does a successful POST request return?
201 (Created) 

### What status code does a successful DELETE request return?
204 (No Content)
