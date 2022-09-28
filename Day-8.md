# Readings: APIs

**API Design Best Practices**

- What does REST stand for?

Overview. A REST API (also known as RESTful API) is an application programming interface (API or web API) that conforms to the constraints of REST architectural style and allows for interaction with RESTful web services. REST stands for representational state transfer and was created by computer scientist Roy Fielding.
- REST APIs are designed around a ____.

REST APIs are designed around resources
- What is an identifier of a resource? Give an example.

A Uniform Resource Identifier (URI) is a character sequence that identifies a logical (abstract) or physical resource -- usually, but not always, connected to the internet. A URI distinguishes one resource from another.
- What are the most common HTTP verbs?

POST, GET, PUT, PATCH, and DELETE
- What should the URIs be based on?

A URI must represent an object, uniquely and permanently
- Give an example of a good URI.

URIs should be short in length. URIs should be case-sensitive
- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Reason why chatty APIs are considered poor quality is because requiring multiple network calls will slow down an application. This is because each call contains data overhead (i.e. sender information, headers, authentication) which will slow down an application as well as network latency per each request
- What status code does a successful GET request return?

The 200 OK status code
- What status code does an unsuccessful GET request return?

If not valid, 400 Bad Request is returned.
- What status code does a successful POST request return?

The 200 OK status code
- What status code does a successful DELETE request return?


A successful response of DELETE requests SHOULD be an HTTP response code 200 (OK)
## Things I want to know about.

- Servers, and how to successfully link them with applications.
