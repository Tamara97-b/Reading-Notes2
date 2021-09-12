## In your own words, describe what each group of status code represents:
## 100’s =
The HTTP 100 Continue informational status response code indicates that everything so far is OK and that the client should continue with the request or ignore it if it is already finished.
## 200’s =
This is a list of Hypertext Transfer Protocol (HTTP) response status codes.
## 300’s =
The data requested actually resides under a different URL, however, the redirection may be altered on occasion (when making links to these kinds of document, the browser should default to using the Udi of the redirection document, but have the option of linking to the final document) as for "Forward".
## 400’s =
The request had bad syntax or was inherently impossible to be satisfied
## 500’s =
The server encountered an unexpected condition which prevented it from fulfilling the request.
## What is a status code 202?
The request has been accepted for processing, but the processing has not been completed. The request may or may not eventually be acted upon, as it may be disallowed when processing actually takes place. there is no facility for status returns from asynchronous operations such as this.
## What is a status code 308?
If the client has done a conditional GET and access is allowed, but the document has not been modified since the date and time specified in If-Modified-Since field, the server responds with a 304 status code and does not send the document body to the client.
## What code would you use if an update didn’t return data to a client?
to your question is use 404 in your case. 204 is a specialized reponse code that you shouldn't often return to a browser in response to a GET .
## What code would you use if a resource used to exist but no longer does?
If the server does not wish to make this information available to the client, the status code 404 (Not Found) can be used instead.
## What is the ‘Forbidden’ status code?
The HTTP 403 Forbidden client error status response code indicates that the server understood the request but refuses to authorize it.
## Why do we need to pull our MongoDB database string out of our server and put it into our .env?
Let Us Handle the Provisioning, Scaling, Back Ups, and Security of Your MongoDB Cluster. Offload the Complex, Time Consuming Administration Tasks to Us. Get Started Today. Simple Pricing. Comprehensive Tutorials. Account Role Permissions.
## What is middleware?
 is software that provides common services and capabilities to applications outside of what's offered by the operating system.
## What does app.use(express.json()) do?
 to recognize the incoming Request Object as a JSON Object.
## What does the /:id mean in a route?
params object, with the name of the route parameter specified in the path as their respective keys. and. app.
## What is the difference beween PUT and PATCH?
The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.
## How do you make a defalut value in a schema?
Declaring Defaults in Your Schema ... Your schemas can define default values for certain paths.
## What does a 500 error status code mean?
The HTTP status code 500 is a generic error response. It means that the server encountered an unexpected condition that prevented it from fulfilling the request.
## What is the difference between a status 200 and a status 201?
The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).