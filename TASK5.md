# Task 5
- Create a simple web application using Next.js that allows users to create and view blog posts. Use AWS DynamoDB to store and retrieve the blog post data. Here's a step-by-step guide on how you can accomplish this task:
  1. Set up your AWS account and create a DynamoDB table for storing blog posts. Choose an appropriate primary key for the table, such as "postId".
  2. Set up the AWS SDK for JavaScript in your Next.js application. You can use the "@aws-sdk/client-dynamodb" package to interact with DynamoDB.
  3. Create a form in your Next.js application that allows users to create a new blog post. When the form is submitted, use the AWS SDK to insert the new blog post data into the DynamoDB table.
  4. Create a page in your Next.js application that displays a list of all the blog posts in the DynamoDB table. Use the AWS SDK to retrieve the blog post data and display it on the page.
  5. Create a page in your Next.js application that displays a single blog post. Allow users to navigate to this page from the list of blog posts page. Use the AWS SDK to retrieve the specific blog post data and display it on the page.

- Optional: Add additional features to your web application, such as the ability to edit or delete blog posts.