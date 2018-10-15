# Players API

An API that simply serves up CRUD functions for Players in the Monday Night Lights Hockey League

## Technology

This API is built with [NodeJS](https://nodejs.org/en/docs/) in the [Serverless Framework](https://serverless.com/framework/docs/) with AWS Lambda.  It was heavily influenced and based off of an example in the [_Serverless/Examples_ repository](https://github.com/serverless/examples/tree/master/aws-node-rest-api-with-dynamodb)  (Thanks!).  It leverages DynamoDB as a data store.

## Development

To setup using `serverless`, follow this [Quick Start guide](https://serverless.com/framework/docs/providers/aws/guide/quick-start/).  Or if you want to just jump into working on the API, you'll want to follow these steps:

### Installing the serverless cli

```npm install -g serverless```

### Setup AWS Ccredentials

```serverless config credentials --provider aws --key {work-with-jeremy-to-get-me} --secret {work-with-jeremy-to-get-me}```

### Navigate to the Repository

```cd path/to/repository```

### Deploy the API

```sls deploy```

After these steps, the API should be deployed.