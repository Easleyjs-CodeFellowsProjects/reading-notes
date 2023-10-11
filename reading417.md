# Reading Notes (401) Reading 17 - easleyjs

AWS S3 and CDNs

## Questions
**What is Amazon S3?**

Object storage/cloud storage on AWS.

**Name some use cases for Amazon S3**

Storing data for mobile or regular web apps, storing large data sets for machine learning, storage backup files

**Name some benefits of using Amazon S3**

Backup and restore features, ability to lower costs if you can move your files into S3 glacier storage, availability for AWS features and via URL.

**What is AWS Lambda?**

A "serverless" platform for running code from various frameworks. It allows you to write Node.js code without having to even create an EBS deployment.

**Name some use cases for AWS Lambdas**

Maintenance, automation, notifications, tasks that don't require a whole server.

**Describe “serverless” to a non-technical friend**

Normally, to deploy a web app, you'd have to set up architecture for the web server, database, and networking. Lambda lets you write code that runs on its platform and handles most of the infrastructure for you, so you can just have it handle requests or access your data.

**What is a CDN?**

Content Delivery Network. A network of servers around the world that allow distributed copies of the same content in order to speed up its delivery.

**How does a CDN work with relation to the website visitor?**

The server closest to the viewer sends them the content.

**What are the benefits of employing a CDN?**

It helps prevent against Denial-of-Service attacks, and also speeds up content delivery.
