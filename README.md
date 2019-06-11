# RESTful APIs Demystified with Express

This tutorial is about **RESTful API**. In addition to discussing what exactly
Restful APIs are and how they are useful, we will also build one using
Node and Express.

Through the process of building a RESTful API, we will highlight key
distinguishing features of the *RESTful* style of doing things versus 
alternative approaches.

## What is an API?

**Application Programming Interfaces** (APIs) are instructions, standards, and
tools designed for human beings to make programs talk to each other (which in
turn may talk to human beings).

For instance, (example of a thing you would want an API for---this is
what we will build)

## What is REST?

According to Wikipedia, **Representational state transfer** (REST) is 

> ...a software architectural style that defines a set of constraints to 
> be used for creating Web services.

In turn, the **architecture** of a software system

> ...is a metaphor, analogous to the architecture of a building.

A *RESTful* API is thus an API designed around a particular set of constraints.

Note that REST is *not* a strictly defined protocol, like SOAP (or
HTTP), but rather a *style* of doing things.


![A well rested cat](https://i.imgur.com/3yvjEKK.jpg)

### The Six Constraints

- **Uniform Interface**: HTTP is used to define the API.
- **Stateless**: Each message sent to the server contains enough information 
  to process the message. *Analogy:* The post office doesn't need to remember 
  which person brought in which package or envelope. This is because this 
  information is contained on the envelope!
- **Cacheable**: Responses sent to clients don't need to come directly from a
  server's database. *Analogy:* Professors like to put commonly asked for
  information on course syllabi. Then, students can consult these documents
  (cache) rather than bothering the professor or teaching assistants.
- **Client-Server**: Clients make request to servers.
- **Layered System**: A client may not be interacting with any one server
  directly. A resource returned to a client may be served from somewhere 
  other than the database (directly): a cache, another server, etc. may serve
  server, etc. may be used to fulfill a client's request
- **Code on Demand** (optional):

We'll discuss more about what these constraints are below as we build a RESTful
API.

## Routes and Endpoints

**Routes**, as you are likely to encounter them working with JavaScript, are
**URIs** mapped to different HTTP methods.

RESTful APIs are *resource-based* versus *action-based*. Rather than talking
about "verbs", we are talking about "nouns". 

Multiple URIs can point to the same resource (EXAMPLE).

## Requests and Responses

In Express, **requests** and **responses** are seen as parameters of 
callback functions.

Requests ask a server for some data.

Responses are the data you get back from the API.

## Making some sentences

A *RESTful* API may allow *CRUD* operations on via *HTTP* methods.

## Links and Resources

- [Representational state transfer](https://en.wikipedia.org/wiki/Representational_state_transfer) on Wikipedia
- [Software architecture](https://en.wikipedia.org/wiki/Software_architecture) on Wikipedia
- [REST API Handbook](https://developer.wordpress.org/rest-api/)  from
  Wordpress.org
- [REST API Tutorial](https://www.restapitutorial.com/)
- [SOAP vs REST vs JSON comparison [2019]](https://raygun.com/blog/soap-vs-rest-vs-json/) on RAYGUN
