# Reading Notes (401) Reading 07 - easleyjs

JSON Web Token (JWT)

## Questions
**What is a JSON Web Token (JWT)?**

A way to securely transfer digitally signed info between parties as a JSON object.

**When should we use JSON Web Tokens?**

For authorization, or when we want to securely transfer information

**Claims are expected in which structural component of a JWT?**

Payload

**If I get a JWT and I can decode the payload, how can we call that secure?**

Because it's encrypted with the secret value

**If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.**

The secret

**Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**

The secret should be sent to the client via an encrypted channel. Once the cleint has the secret value, they can use that to send and recieve messages

**Why use JWT?**

JWT is Compact and self-contained. 

**Describe how this is useful to a non-technical friend.**

It allows us to implement JWT without a lot of overhead either in the app, or in the data we're transmitting

**What are the three components (the structure) of a JWT signature?**

Header, Payload, Signature
