# Serverless-Notify

*Solution Overview* 


In this use case, we leverage AWS serverless components – Lambda, API Gateway, and DynamoDB – to create a system that sends SMS notifications to users submitting inquiries via a website contact form outside business hours. AWS Lambda executes code logic, checking timestamps in DynamoDB to ensure timely responses, while API Gateway facilitates user-triggered events. This serverless architecture not only ensures cost-effective scalability but also optimizes resource usage by charging only for the executed functions.

Read the full blog here : 
![ServerLess drawio (1)](https://github.com/Saumil343/Serverless-Notify/assets/53990452/05c2e071-b5a9-492c-81e0-9c45f9acee6b)


*Prerequisites*
1. Configure SNS service, if you are using SandBox make sure you have a verified phone number in the AWS SNS-SMS section.
2. Use test JSON in the API gateway with the created phone number
3. Configure AWS account number in 'terraform.tf' file
4. Brainstorm a little more and change the logic as per use case in lambda function code ;-) .
