# Reading Notes (401) Reading 19 - easleyjs

AWS SNS and SQS

## Questions
**What is the difference betweeen SQS and SNS?**

Simple Queueing Service is for storing messages. Simple Notification Service is for sending and recieving notifications.

**What are some use cases for both SNS and SQS?**

SNS - Sending app notifications when messages arrive.
SQS - Storing app messages until they are ready to be pulled.

**Describe how to use SQS and SNS in a “fanout” pattern.**

A SNS can send a notification to many subscribers.

**Explain how “push notifications” work, using SNS.**

An app/service would be a subscriber to an event topic. When an event occured in the topic, you would recieve a message from SNS.

**How might a large scale, distributed application make use of a Queue system like SQS?**

When someone sends a message on a social media type app, maybe it sits in a queue for the appropriate user, until that user logs on and pulls their messages.
