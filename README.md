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
|Client|An application making protected resource requests on behalf of the resource owner and with its authorization|
|Resource Server|The server hosting the protected resources|
|Authorization Server|The server issuing access tokens to the client after successfully authenticating the resource owner and obtaining authorization|

### OAuth 2.0 Client Types

|---|---|
|:--|:--|
|Confidential Clients|Clients capable of maintaining the confidentiality of their credentials. (On the server)|
|Public Cleints|Clients incapable of maintaining the confidentiality of their credentials. (Native Applcations, User-Agent based applications)|

### OAuth 2.0 Endpoints

|---|---|
|:--|:--|
|Server Authorization endpoint|used by the client to obatin authorization from the resource owner via user-agent redirection|
|Server Token endpoint|used by client to exchange an authorization grant for an access token, typically with client authentication|
|Client Redirection endpoint|used by the authorization server to return responses containing authorization credentials to the client via the resource owner user-agent|

### IdentityServer v3

Created by @leastprivilege and @brockallen

Implements OAuth 2.0 and OpenID Connect

Highly optimized to solve the typical security problems of today's mobile, native and web applications.

Part of the .NET Foundation

[https://identitysever.github.io](https://identitysever.github.io)

## Authorizing Access to the API

### Client Credentials Flow

Machine to machine communication. No human involved: no username/password. It can be used to obtain access tokens using client credentials.

## Understanding Identity: OpenID Connect

## Working with OpenID Connect on the Client

## Impersonating the User When Accessing the API

## Advanced Topics

## Dealing With Credentials

