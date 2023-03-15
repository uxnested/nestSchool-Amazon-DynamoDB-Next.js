# Task 2
- Create a Next.js web application that connects to an AWS DynamoDB table and displays the items in the table on a web page.
  
* ### Steps: 
    1. Set up your Next.js project:
           - Create a new Next.js project using the command line or your preferred IDE.
           - Install the AWS SDK for JavaScript package: <code>npm install aws-sdk </code>
           - Import the DynamoDB client from the AWS SDK in your project.           
    2. Connect to the DynamoDB table:
          - Create a new instance of the DynamoDB client with your AWS credentials and the correct region.
          - Use the scan method to retrieve all items in the table.
          - Store the items in an array. 
    3. Display the items on a web page:
          - Create a new page in your Next.js project.
          - Use the getServerSideProps function to retrieve the items from the DynamoDB table and pass them as props to the page component.
          - Map through the items array in the component and display them on the page. 
    4. Test your application:
          - Run your Next.js project and navigate to the page you created.
          - Verify that the items in the DynamoDB table are displayed correctly on the page.
- 📓 You will need to have an existing DynamoDB table with items in it to complete this task. If you don't have one, you can create one by following the instructions below. 
- ### Dynamodb Load a Table
      https://www.tutorialspoint.com/dynamodb/dynamodb_load_table.htm

