**Shubham's Review**

## Question 1 
Used cli and boto to create roles and ec2 instances 

## Question 2
For starting part, used boto3 to create roles and policies and then from gui created lambda function with lambda_handler.py. Proper logs were generated and the file also got uploaded to the bucket. 

## Question 3
Created an POST API on API Gateway, for sending the api from local machien he used curl method and provided the link for the api created.


**Kushagra's Review**

In Task 1, the code successfully creates an IAM role, attaches a policy, creates an S3 bucket, and launches an EC2 instance. The code is concise and uses appropriate method calls to achieve the desired actions.

In Task 2, the code imports the necessary libraries, generates a JSON object with transaction details, uploads the JSON file to an S3 bucket, and publishes a log message to CloudWatch Logs. The code appropriately handles exceptions and includes log group and log stream creation if they don't exist. 
The naming conventions for the S3 bucket, key name, log group, and log stream are clear and meaningful.

In Task 3, the code imports the necessary libraries, parses input data, generates a timestamp, uploads a JSON file to an S3 bucket, and prints a log message. The exception handling is well-implemented, and the code returns an appropriate response dictionary based on the execution status.
The use of timestamps in the key name and JSON data ensures uniqueness and organization.
