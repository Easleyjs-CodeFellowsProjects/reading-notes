# Reading Notes (401) Reading 18 - easleyjs

AWS API Gateway, Dynamo, and Lambda

## Questions
**What is Amazon API Gateway?**

An AWS service that allows you to create REST and HTTP routes similar to Express.

**Why is Amazon API Gateway an important part of the Serverless ecosystem?**

It allows you to call Lambda functions without having to set up a server on EBS/EC2.

**How does API Gateway integrate with other AWS services?**

It allows you to call lambda functions, notifications, and handle auth functions

**What are the some benefits of using Amazon API Gateway?**

Eliminates need for a dedicated API server. Provides built-in logging options. Lets you easily connect to lambda functions.

**What two API types might you choose from?**

REST and WebSockets

**What is DynamoDB?**

An AWS NoSQL DB.

**Under what circumstances would you recommend DynamoDB over MongoDB?**

It integrates easily with Lambda functions, IAM, and the API gateway.

**Explain to a non-technical friend how DynamoDB works**

Dynamo DB lets you store data in AWS in a way that's pretty similar to native Javascript. Then, it can be easily accessed with a package of code called Dynamoose.

**What is Dynamoose?**

Dynamoose is an ORM (obj. relation mapper) for AWS DynamoDB.

**What are some key features of Dynamoose?**

Provide an easy way to perform CRUD operations on DynamoDB collections/models. Provides a lot of functionality similar to Mongoose.
