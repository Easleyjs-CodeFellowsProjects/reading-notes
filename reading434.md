# Reading Notes (401) Reading 34 - easleyjs

OAuth API Integration

## Questions
**Explain the different between a query string parameter and a path parameter.**

Query string is passed as text appened to the end of the URL after a "q=". It could be used to specify settings.

A path parameter is part of the URL, and is typically used to specify a URI and id of a model.

**What would our API URL with a path id parameter be given the following information:
Domain: http://our-site.com
v3
model name: stuff
id: things**

This would use the "v3" router, targeting the "stuff" model with an id of "things".

**We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.**

Our API is able to require authentication - a user either signing in with login/password, or with a JSON Web Token which they could get from a third-party authorizing service which might use their Google or Facebook credentials.

**Describe how you would use middleware to implement basic and bearer auth.**

We could create a route that examines the Authorization header and verifies either the username/password, or the auth token before allowing access to the routes on our backend.

**Describe the handshake necessary to implement OAuth.**

Client redirects user to authorization endpoint of the OAuth provider. User confirms that they want to grant access to app.

Client exchanges grant for a token from the provider.

Client makes a request on the app using the token.


**Describe how Role Based Access Control works to a non-technical friend.**

Instead of giving someone a set of permissions to do certain things in an app, we would assign them to a role which had established permissions to perform certain tasks.
