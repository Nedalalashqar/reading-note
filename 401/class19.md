# AWS: Events

## Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

> both uses RESTful api and uses HTTP for res/req ,Key Authentication ,HTTPS,CORS,oAuth2 ,both uses function to handle those requests and create proper response.

## List the AWS Database offerings and talk about the pros and cons of each
* **Amazon RDS** : Managed Relational Database Service for MySQL, PostgreSQL, MariaDB, Oracle BYOL, or SQL Server and can’t be integrated with lambda function in aws. 
* **Amazon DynamoDB** :Fast and flexible NoSQL database with seamless scalability and can be integrated with lambda function in aws.
* **Amazon ElastiCache**
* **Amazon Timestream**

## What’s the difference between a FIFO and a standard queue?

> Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue

## How can the server be assured a message was properly received?

> by listening to a received event triggered when the message received ,