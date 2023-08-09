# Roles, Claims and JWT Tokens

## Claims-based authorization
When an identity is created it may be assigned one or more claims issued by a trusted party. A claim is a name value pair that represents what the subject is, not what the subject can do. For example, you may have a driver's license, issued by a local driving license authority. Your driver's license has your date of birth on it. In this case the claim name would be DateOfBirth, the claim value would be your date of birth, for example 8th June 1970 and the issuer would be the driving license authority. 
Claims in code specify claims which the current user must possess, and optionally the value the claim must hold to access the requested resource. Claims requirements are policy based, the developer must build and register a policy expressing the claims requirements.

## Andrew Lock | .NET Escapades
### The difference between Authentication and Authorisation
First of all, we should clarify the difference between these two dependent facets of security. The simple answer is that Authentication is the process of determining who you are, while Authorisation revolves around what you are allowed to do, i.e. permissions. Obviously before you can determine what a user is allowed to do, you need to know who they are, so when authorisation is required, you must also first authenticate the user in some way.

## JWT to authenticate Servers API’s
JSON Web Token (JWT) is a means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signature (JWS) and/or encrypted using JSON Web Encryption (JWE).

In simple terms, it is just another way of encoding JSON object and use that encoded object as access tokens for authentication from the server.
