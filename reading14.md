# Reading Notes 14 - easleyjs

## Overview
OAuth and OpenID

## Things I want to know more about
How OpenID is used in conjunction with users having individual accounts.

## Reading Questions

**What is OAuth?**

An open-standard framework that describes how unrelated servers can share assets without sharing the initial logon credential.

**Give an example of what using OAuth would look like.**

You click on a button that says "Logon using GitHub" and you authenticate with GitHub to then use the site you're on.

**How does OAuth work? What are the steps that it takes to authenticate the user?**

User signs into first website.
First website connects to second website using OAuth.
Second site generate a one-time token and secret.
First site gives this token and secret to user's client.
Client present token and secret to auth provider.
If not authenticated, client may be asked to authenticate.
Client approves the transaction on first site.
Client is given approved access token.
Token is given to first site.
First site gives token to second site.
Second site lets first site user access site on their behalf.
Client sees successful transaction.

**What is OpenID?**

A framework for passing authentication instead of authorization.

**What is the difference between authorization and authentication?**

Authorization is when a site allows you to login on their behalf. Authentication is when you log in and gain access.

**What is Authorization Code Flow?**

The passing of authorization between the web app, user, and an API.

**What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?**

Addition of a secret that the can be verified by the authorization server.

**What is Implicit Flow with Form Post?**

Simplified process that only uses a token, not a secret.

**What is Client Credentials Flow?**

A process for back-end processes to authenticate and authorize.

**What is Device Authorization Flow?**

A method for authenticating devices where it would be cumbersome to require a username/password. They can just go to a link instead.

**What is Resource Owner Password Flow?**

Where credentials are passed directly using a form. Most insecure method.
