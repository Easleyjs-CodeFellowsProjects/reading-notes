# Reading Notes 11 - easleyjs

## Overview
CRUD

## Things I want to know more about

-- Reading Questions
**In your own words, describe what each group of status code represents:**

- 100’s = Informational
- 200’s = Success
- 300’s = 200 with add'l info
- 400’s = Request Errors
- 500’s = Server Errors

**What is a status code 202?**

Request was accepted and will be processed at some point

**What is a status code 308?**

Permanent Redirect

**What code would you use if an update didn’t return data to a client?**

204

**What code would you use if a resource used to exist but no longer does?**

410

**What is the ‘Forbidden’ status code?**

403

**Why do we need to pull our MongoDB database string out of our server and put it into our .env?**

So we can easily swap in production url when ready, and so it's hidden

**What is middleware?**

Code that runs before request is passed to routes

**What does app.use(express.json()) do?**

Converts responses to json

**What does the /:id mean in a route?**

Used to provide an (id) parameter

**What is the difference between PUT and PATCH?**

PUT overwrites the whole record, patch is for changing parts of the record

**How do you make a default value in a schema?**

Add a property for "default"

**What does a 500 error status code mean?**

There was an error on the server

**What is the difference between a status 200 and a status 201?**

200 means the request was successful. 201 means it was successful and a record was created
