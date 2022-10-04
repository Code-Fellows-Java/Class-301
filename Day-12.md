# Readings: CRUD

**Status Codes Based On REST Methods**

- In your own words, describe what each group of status code represents:

100’s =  everything so far is OK and that the client should continue with the request or ignore it if it is already finished.
200’s = The Request has been accepted.
300’s = The request has multiple repsonses possible
400’s = The server can't or won't process the request.
500’s = Internal server error.


- What is a status code 202?

The request has been accepted for processing, but the processing has not been completed. 
- What is a status code 308?

The resource requested has been definitively moved to the URL given by the Location headers
- What code would you use if an update didn’t return data to a client?

204 No Content
- What code would you use if a resource used to exist but no longer does?

409 Conflict
- What is the ‘Forbidden’ status code?

HTTP 403 

**Build A REST API With Node.js, Express, & MongoDB**

- Why do we need to pull our MongoDB database string out of our server and put it into our .env?

Without a connection string, we cannot connect to the database server, we need a connection string to connect the database server.
- What is middleware?

Middleware is software that lies between an operating system and the applications running on it
- What does app.use(express.json()) do?

This method is used to parse the incoming requests with JSON payloads and is based upon the bodyparser
- What does the /:id mean in a route?

Tt's a dynamic route
- What is the difference between PUT and PATCH?

PUT is a method of modifying resource where the client sends data that updates the entire resource . PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.
- How do you make a default value in a schema?

You can specify a default value for an item using the default keyword
- What does a 500 error status code mean?

500 Internal Server Error
- What is the difference between a status 200 and a status 201?

The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created

## Things I want to know more about.

- Vanilla JS
