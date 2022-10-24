
[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 19 - AWS: AWS: API, Dynamo and Lambda

## Discussion Questions

### AWS SQS vs SNS

What is the difference betweeen SQS and SNS?
> SNS is a distributed publish/subscribe service while SQS is a distributed queue service.

What are some use cases for both SNS and SQS?
> SNS:To send messages to email, cell phone, other AWS services etc.
> SQS: Allows client to pull the stored message from queue. Good for micro-services,serverless apps and distributed systems.

### AWS SNS and SQS

Describe how to use SQS and SNS in a “fanout” pattern.
> Use SNS to send message with info. The info can be split up and only certain data can be sent to different subscriber's for their purpose. The queue client can then pull the info to use as needed. Different clients get the info they need to do their function.

Explain how “push notifications” work, using SNS.
> Multiple clients can subscribe to an event. When the event gets published, all the subscribers then can respond appropriately.

### SQS and SNS Basics

How might a large scale, distributed application make use of a Queue system like SQS?
> Tie in different client interfaces into the queue and the ability to scale up the queue. The app can also use the queue as a buffer to retain messages and distribute them to the end clients with many different purposes. The idea is that all subscribers can receive the message once and having 1 subscribers not receive message will not break the system. Each piece of the app can do their work when they are able to do so.

## Things I want to know more about

How to compartmentalize the system to handle all the aspects of the queue system. Seems more complicated than previous instances of queue that I've done.

-----
