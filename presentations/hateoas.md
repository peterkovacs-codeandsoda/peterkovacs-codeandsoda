<style>
.page-header {
  background-image: none;
}
</style>
# REST & HATEOAS

## 1. The RESTful style

### 1.1. Architetural constraints
- Client-server architecture
- Statelessness
- Cacheability
- Layered system
- Uniform interface
- Code on demand (optional)
  - Javascript as a response

### 1.2. Semantics of HTTP methods
- GET/PUT/DELETE idempotent operations
- GET/POST cacheable
- CRUD
  - Create: PUT
  - Read: GET
  - Update: PUT
  - Delete: DELETE
- POST /api/addtocart vs PUT /api/user/{userId}/cart/{productId} {"quantity": 2, "salesUnit": "H04"}

## 2. Uniform interface
- Resource identification in requests
- Resource manipulation through representation
- Self-descriptive messages
- Hypermedia As The Engine Of Application State

## 3. Hypermedia As The Engine Of Application State - HATEOAS

### 3.1. What is Hypermedia?
- extension of hypertext
- graphics
- audio
- video
- plain text
- hyperlink

### 3.2. Purpose of HATEOAS
- decouple server and client
- server-provided links to dinamiccaly discover resources, actions and operations
- no need for hard-coded URIs
- the server can change URI anytime (API evolution)

### 3.3. Implementing HATEOAS
- [RFC 5988](https://tools.ietf.org/html/rfc5988)
- [JSON Hypermedia API Language(HAL)](https://en.wikipedia.org/wiki/Hypertext_Application_Language)

## 4. Why no Global Victory?
- missing REST crawlers
- no clients created to consume this type of API
- less practical than theoretical
