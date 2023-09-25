# Reading Notes (401) Reading 05 - easleyjs

Authentication

## Questions

**Explain to a non-technical friend how you would safely hash and store a password.**

The user would sent a password to the server, the server would then encrypt that password by using the bcrypt code library to scramble the characters so that they can only be read by the server.

**What is Bcrypt?**

A javascript library for encryption

**Why might you use something like Bcrypt?**

To encrypt and decrypt passwords without having to write your own algorithm.

**What is Basic Authentication?**

Username and password

**What properties are necessary in the header of a Basic Auth request?**

Authorization: Basic username:password

**How are username:password in Basic Auth encoded?**

With Base64

**Define the authentication process to a non-technical recruiter.**

The process of verifying that a user is who they're saying they are. A user's client send their credentials which are then checked against an encrypted copy stored in the database.

**How should your error messaging respond (both HTTP and HTML)? Why?**

In a generic manner. You don't want to reveal details about the account or the authentication by giving away any details.

**Looking ahead at this module’s course schedule, What do you look forward to learning?**

Storing accounts in a db
