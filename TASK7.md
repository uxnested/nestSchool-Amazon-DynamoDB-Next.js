# Task 7
- Create a serverless API using AWS Lambda and API Gateway in your Next.js application. Use the API to retrieve and store data in a DynamoDB table. Here's a step-by-step guide on how you can accomplish this task:
    1. Set up your AWS account and create a DynamoDB table for storing data. Choose an appropriate primary key for the table, such as "itemId".
    2. Set up the AWS SDK for JavaScript in your Next.js application. You can use the "@aws-sdk/client-dynamodb" package to interact with DynamoDB.
    3. Create a Lambda function in AWS that retrieves data from the DynamoDB table. Use the AWS SDK to retrieve data from the table.
    4. Create an API Gateway endpoint in AWS that triggers the Lambda function when it receives an HTTP request. Use the AWS API Gateway console to create the endpoint.
    5. Create a page in your Next.js application that displays the data retrieved from the Lambda function.
    6. Create a form in your Next.js application that allows users to submit new data to the DynamoDB table via the API Gateway endpoint.
- Optional: Add additional features to your web application, such as the ability to edit or delete data from the DynamoDB table.
