# Overview of Architecture

We will use the following AWS services:
* AWS Lambda: To run PHP code serverlessly.
* Amazon API Gateway: To route HTTP requests to Lambda functions.
* Amazon Aurora Serverless: As a managed, serverless MySQL-compatible database.
* Amazon S3: To store and serve media files.
* Amazon CloudFront: For content delivery and caching.

# Step 1: Setting Up Amazon Aurora Serverless for MySQL
## 1.1 Log in to AWS Management Console :
Navigate to the AWS Management Console and log in with your credentials.

## 1.2 Create an Amazon Aurora Serverless Database

