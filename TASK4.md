# Task 4
1. Create a DynamoDB table with a partition key "userId" and a sort key "timestamp". Use the GUI Console to create the table and add some sample data.
2. Query the DynamoDB table you created in step 1 using JavaScript. Write a JavaScript/TRypeScript program that retrieves all items with a specific "userId" using the query method.
3. Create a Next.js application that retrieves data from the DynamoDB table you created in step 1
   - Use the AWS Amplify library to connect to the DynamoDB table and retrieve data. Display the data on a webpage.  
4. Create a secondary index on the DynamoDB table you created in step 1
   - The secondary index should have a partition key "category" and a sort key "timestamp". Use the GUI Console to create the secondary index. 
5. Query the secondary index you created in step 4 using JavaScript/Typescript. Write a TypeScript program that retrieves all items with a specific "category" using the query method.
6. Query the secondary index you created in step 4 using TypeScript. Write a JavaScript/TypeScript program that retrieves all items with a specific "category" using the query method.
7. Update the Next.js application you created in step 3 to retrieve data from the secondary index you created in step 4. Use the AWS Amplify library to connect to the secondary index and retrieve data. Display the data on a webpage.
8. Create a scan operation to retrieve all items from the DynamoDB table you created in step 1. Use the GUI Console to perform the scan operation.
9. Modify the scan operation you created in step 7 to filter the results based on a specific attribute. Use the GUI Console to perform the filtered scan operation.
10. Update the TypeScript program you created in step 2 to use the scan method instead of the query method. Use a filter expression to retrieve items with a specific attribute.
11. Update the Next.js application you created in step 6 to allow users to filter data based on a specific attribute. Use a form input to accept user input and use the filter expression to retrieve the filtered data. Display the filtered data on a webpage.

- ### Dynamodb API Interface:
    https://www.tutorialspoint.com/dynamodb/dynamodb_api_interface.htm
