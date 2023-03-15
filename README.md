# beginner to an intermediate-level understanding of DynamoDB with Next.js

<p>To get started with learning AWS DynamoDB, here are some steps you can take.
You can use tools like Node.js, npm, and code editors like Visual Studio Code.
</p>

 1. ### Basics of AWS DynamoDB 
    * Familiarize yourself with the DynamoDB data model, concepts, and API. You can start by reading the [official documentation](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html) and following tutorials.
 2. ### Setup Environment
    * Install Node.js and a code editor like Visual Studio Code on your computer.
 3. ### Learn Next.js
    * Next.js is a popular React framework for building server-side rendered web applications. You can start by reading the [official documentation](https://nextjs.org/docs/getting-started) and following the tutorials
 4. ### Learn how to use AWS SDK for JavaScript
    * The AWS SDK for JavaScript is a collection of libraries for interacting with AWS services from your JavaScript application. You can use it to interact with DynamoDB from your Next.js application. You can start by reading the [official documentation](https://docs.aws.amazon.com/sdk-for-javascript/v3/developer-guide/dynamodb-example-query-scan.html)  and following the tutorials.
 5. ### Practice building applications with DynamoDB
    * Create sample applications using DynamoDB and Next.js to practice and solidify your understanding of the technology.
 6. ### Use Unit testing
    * Unit testing is an important aspect of software development. Write unit tests for your applications to ensure they are working correctly. 
 7. ### Explore advanced topics
    * Once you have a good grasp of the basics, you can explore more advanced topics like data modeling, indexing, and optimization.

- ### Remember, the most effective way to learn is by doing. So, as you learn, practice building applications using DynamoDB and Next.js.

# Basic Overview of AWS

- DynamoDB allows users to create databases capable of storing and retrieving any amount of data and serving any amount of traffic. It automatically distributes data and traffic over servers to dynamically manage each customer's requests, and also maintains fast performance.
    ## 1. Advantages  
        1. The two main advantages of DynamoDB are scalability and flexibility. It does not force the use of a particular data source and structure, allowing users to work with virtually anything, but in a uniform way.
        2. Its design also supports a wide range of use from lighter tasks and operations to demanding enterprise functionality. It also allows the simple use of multiple languages: Ruby, Java, Python, C#, Erlang, PHP, and Perl.
        3. DynamoDB does suffer from certain limitations, however, these limitations do not necessarily create huge problems or hinder solid development.
    ## 2. Limitations
        1. Capacity Unit Sizes − A read capacity unit is a single consistent read per second for items no larger than 4KB. A write capacity unit is a single write per second for items no bigger than 1KB.
        2. Provisioned Throughput Min/Max − All tables and global secondary indices have a minimum of one read and one write capacity unit. Maximums depend on region. In the US, 40K read and write remains the cap per table (80K per account), and other regions have a cap of 10K per table with a 20K account cap.
        3. Provisioned Throughput Increase and Decrease − You can increase this as often as needed, but decreases remain limited to no more than four times daily per table.
        4. Table Size and Quantity Per Account − Table sizes have no limits, but accounts have a 256 table limit unless you request a higher cap.
        5. Secondary Indexes Per Table − Five local and five global are permitted.
        6. Projected Secondary Index Attributes Per Table − DynamoDB allows 20 attributes.
        7. Partition Key Length and Values − Their minimum length sits at 1 byte, and maximum at 2048 bytes, however, DynamoDB places no limit on values.
        8. Sort Key Length and Values − Its minimum length stands at 1 byte, and maximum at 1024 bytes, with no limit for values unless its table uses a local secondary index.
        9. Table and Secondary Index Names − Names must conform to a minimum of 3 characters in length, and a maximum of 255. They use the following characters: AZ, a-z, 0-9, “_”, “-”, and “.”.
        10. Attribute Names − One character remains the minimum, and 64KB the maximum, with exceptions for keys and certain attributes.
        11. Reserved Words − DynamoDB does not prevent the use of reserved words as names.
        12. Expression Length − Expression strings have a 4KB limit. Attribute expressions have a 255-byte limit. Substitution variables of an expression have a 2MB limit.