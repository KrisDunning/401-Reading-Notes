[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 18 - AWS: AWS: API, Dynamo and Lambda

## Discussion Questions

### AWS API Gateway Overview

What is Amazon API Gateway?
> Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.

Why is Amazon API Gateway an important part of the Serverless ecosystem?
> API Gateway is the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: it enables a truly serverless architecture for web applications.

How does API Gateway integrate with other AWS services?
> AWS Lambda: run Lambda functions to generate HTTP API responses.
> AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
>Amazon Cognito: provide authentication and authorization for your HTTP APIs.
>API Gateway supports direct integrations that can be configured in the API Gateway user interface (or via the API Gateway’s own API) for the following actions:
>Invoking an AWS Lambda function.
>Invoking another HTTP endpoint, with or without VPC Link.
>Making an HTTP call against the API of any AWS service that provides an HTTP API.
>Returning a mock response generated within API Gateway without calling out to other services

### AWS API Gateway

What are the some benefits of using Amazon API Gateway?
> Efficient API devlelopment, flexible security controls, RESTful API options and performance at any scale.

What two API types might you choose from?
> HTTP or RESTful.

### AWS DynamoDB Guide

What is DynamoDB?
> A hosted NoSQL database hosted on AWS.

Under what circumstances would you recommend DynamoDB over MongoDB?
> Extremely large datasets, and when creating a serverless application that integrates with AWS Lambda.

### AWS DynamoDB

Explain to a non-technical friend how DynamoDB works.
> Its like how a library works. Milllions of books with information like author, genre, character names etc. You can secure age-restricted items. You can sort by genre or author. You can checkout the books, or send them to another library at a customers request. All this but for information like video game data, or social media meta data.

### Dynamoose

What is Dynamoose?
> A modeling tool for DynamoDB.

What are some key features of Dynamoose?
> Easy to use syntax, callback support, multi-regional support, Type safety and able to transform data before saving or retrieving data.

## Things I want to know more about

Just what doesn't AWS do? How does  NoSQL work again? 

-----
