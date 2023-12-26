# AWS-Website
Website deploying in AWS

1. ArcGIS - for map
2. store/update/pull code - Github / CodeCOmmit- you can use github also- We took the code from this, aws s3 cp s3://wildrydes-[your_region_name, like us-west-2]/WebApplication/1_StaticWebHosting/website ./ --recursive
3. permission for the code -- IAM
4. hosting website and make updates -- You can use codeCommit or github and then connect that with Amplify to deploy your code, you can also changes something inside the code and check if amplify working with continuous development or not
5. User to register and log in - cognito [userPool] ( used to authentication)
6. ride sharing functionality (user will request a ride, and unicorn wll go)-- for this we will use Lambda, basically Lambda will help us to run code serverlessly ipon some tigger 
7. store.return ride results -- We will use a NoSql Databases (key-value) which is DynamoDB
So in general user will request a ride then a unicorn will be sent and that ride things will be save in a Table. For that Firstly set up the DynamoDB , then the Lambda function
8. invoke ride sharing functionality -- API Gateway ( Rest API)

![Alt text](image-1.png)

9. Then the integration of the map


![Alt text](image.png)
