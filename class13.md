# Readings for Class13: CRUD

![CRUD](https://miro.medium.com/max/1400/1*2eBdh0vLZjUyCDF6x1EqvQ.png)

## Status Codes Based On REST Methods.
1.
100 :tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client

200: These are the success codes. They tell the client that its request was accepted

300: They tell the client that the resource they are requesting isn’t available at the expected location anymore

400: hese are the client error codes. They are all about invalid requests a client sent to a server.

500: These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, 


2. the request was successfully processed only that it met all validation requirements at the time of sending.

3. the resource requested has been definitively moved to the URL given by the Location headers.

4. 204 

5. 202

6. The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.


1. because when we deploy our application to netlify they will be an erorr

2. Middleware is a type of computer software that provides services to software applications beyond those available from the operating system

3. make the server accept the json as body

4.

5. The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource

6.

7. something has gone wrong on the web site's server 

8. 200:request was received and understood and is being processed.
   201:s that a request was successful and as a result, a resource has been created