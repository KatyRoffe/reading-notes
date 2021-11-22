# Events

1. Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

    - they both respond to HTTP requests that are designed with REST in mind and map CRUD methods

2. List the AWS Database offerings and talk about the pros and cons of each

- Aurora, 5x faster than standard MySQL db's at a low cost
- Relational Database Service, can be easily resized
- RDS, lets you deploy db's in a VMware environment
- DynamoDB, key-value based, can handle high traffic
- ElastiCache, improves web application performance
- Neptune, quickly query graph db's
- QLDB, best way to track changes over time
- Timestream, one of the fastest growing datatypes
- DocumentDB, supports MongoDB workloads

3. What’s the difference between a FIFO and a standard queue?

    - first-in-first-out, exactly-one processing
    - standard queue, at-least-once processing

4. How can the server be assured a message was properly received?

    - send a return message
    - or console.log

## Vocab

- **Serverless API**: an API running on a serverless provider
- **Triggers**: how you get specific thingsto run
- **Dynamo vs Mongo**:
    - Mongo: self-installed or managed through Atlas. JSON-like documents.
    - Dynamo: fully managed AWS server. Uses tables, items, and attribues.
- **Dynamoose vs Mongoose**: dynamoose is strictly for AWS Dynamo

## Materials

- [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)
- [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)
- [SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)
- [SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)