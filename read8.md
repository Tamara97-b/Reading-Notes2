
## What does REST stand for?
A REST API (also known as RESTful API) is an application programming interface (API or web API) that conforms to the constraints of REST architectural style and allows for interaction with RESTful web services. REST stands for representational state transfer and was created by computer scientist Roy Fielding.
## REST APIs are designed around a ____.
## What is an identifer of a resource? Give an example.
The target of an HTTP request is called a "resource", whose nature isn't defined further; it can be a document, a photo, or anything else. Each resource is identified by a Uniform Resource Identifier (URI) used throughout HTTP for identifying resources.
## What are the most common HTTP verbs?
POST, GET, PUT, PATCH, and DELETE
## What should the URIs be based on?
Uniform Resource Identifier
## Give an example of a good URI.
URIs should follow a predictable, hierarchical structure to enhance understandability and, therefore, usability: predictable in the sense that they're consistent, hierarchical in the sense that data has structure—relationships. RESTful APIs are written for consumers
## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. George Reese has defined chatty API as any API that requires consumer to do more than a single call to perform a single, common operation.
## What status code does a successful GET request return?
This means the request was successful and the server created a new resource. This means the server has accepted the request for processing, but the processing has not been completed. This means the server successfully processed the request, but is returning information that may be from another source.
## What status code does an unsuccessful GET request return?
If not valid, 400 Bad Request is returned. Order is processed. If the order is successful, a 201 Created is returned for the order. If an unexpected error is encountered, a 500 Server Error is returned.
## What status code does a successful POST request return?
This means the request was successful and the server created a new resource. This means the server has accepted the request for processing, but the processing has not been completed. This means the server successfully processed the request, but is returning information that may be from another source.

## What status code does a successful DELETE request return?
A successful response of DELETE requests SHOULD be HTTP response code 200 (OK) if the response includes an entity describing the status, 202 (Accepted) if the action has been queued, or 204 (No Content) if the action has been performed but the response does not include an entity.

## Things I want to know more about
delete request 