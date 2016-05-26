## Understanding OAuth 2.0 Basics

> "The era of token-based security".

> OAuth 2.0 is an open protocol to allow secure authorization in a simple and standard method from web, mobile and desktop applications.

OAuth 2.0 isn't about authentication. It's about authorization. The standard doesn't say anything about the user.

- Where can the token be delivered to?
- Can the client appication safely store secrets?

### OAuth 2.0 Flows

It's about making the right decision for the type of application you're building: "how can you safely achieve authorization?".

Flows:

- Client Credentials
- Authorization Code
- Implicit
- Resource Owner Password Credentials

### The Main Actors

|---|---|
|:--|:--|
|User (Resource Owner)|An entity capable of granting access to a protected resource|