# Devops Test

>## To do:-
- Write a cloudformation template to deploy lambda function with api gateway.
- Create a serverless project, add the following functions:-
    1. A lambda function that executes using api gateway.
    2. A lambda function that executes using cron job on every monday at 6 pm.
    3. A lambda function that executes everytime there is a new file the s3 bucket linked to it.
    4. A lambda function that executes when there is a new message in the sqs.
- Create a bucket policy in which only one IAM user can access bucket objects, and bucked is private to everyone else.
- Create a file with the code to create to create signed url which is valid for 1 minute.
- Create a Dockerfile which can be used to deploy a node and express app.
- Create a Dockerfile which can be used to deploy a react app.
- Create docker compose files for both apps.
- How would you trigger a lambda 10 minutes after each entry to the database.
- Suppose your lambda sends this information to the logs 
<br /><code>Order 1112312 execution success</code>
<br /><code>Order 2312421 execution failed</code>
<br />Write a cloudwatch query to just get the following information
<br /><code>1112312, success</code>
<br /><code>2312421, failed</code>

>## Extra points:-
- Create an ECS cluster and Task definition, that is executed through a cron job everyday.
- Create an ECS cluster and Task definition, that is executed through a lambda.
>## Things to keep in mind:-
- Just create one single repo and add all your files for each step in a different folder.
- Make sure you ran everything locally or on AWS, because we will deploy your code on AWS to test it, so it should be working properly.
- All code and examples should be based on node image and environment.
- Serverless is a framework used to manage and deploy serverless code.
- Do not spend more than **one** day on this test, it's fine to not finish it. A few questions are going to came after the code review and that's the important part.
