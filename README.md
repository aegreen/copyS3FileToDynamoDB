# copyS3FileToDynamoDB

## Note: Does not use a separate plugin, hooks into S3 event
## Copies data to DynamoDB table on S3 upload event

Uses Serverless.com and node.js

## Serverless deployment creates:
- S3 bucket
- DynamoDB Table
- Lambda function that copies the file data from the S3 bucket into DynamoBD table

Uses uuid and aws-sdk node modules



## Setup
Run the command below to add dependencies

```bash
npm install
```

Will require serverless install

## Deploy
Run the following command in order to deploy

```bash
serverless deploy
```
