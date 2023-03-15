# Task 6
- Create a contact form in your Next.js application that allows users to send messages to a specified email address. Use AWS DynamoDB to store the contact form data, including the user's name, email address, and message Here's a step-by-step guide on how you can accomplish this task:
    1. Set up your AWS account and create a DynamoDB table for storing contact form data. Choose an appropriate primary key for the table, such as "messageId".
    2. Set up the AWS SDK for JavaScript in your Next.js application. You can use the "@aws-sdk/client-dynamodb" package to interact with DynamoDB.
    3. Create a contact form in your Next.js application that allows users to enter their name, email address, and message. When the form is submitted, use the AWS SDK to insert the contact form data into the DynamoDB table.
    4. Set up AWS Simple Email Service (SES) to receive and send email. Configure SES to send email to a specified email address when a new message is received.
    5. Create a page in your Next.js application that displays a list of all the contact form messages in the DynamoDB table. Use the AWS SDK to retrieve the contact form data and display it on the page.
- Optional: Add additional features to your web application, such as the ability to delete contact form messages.
