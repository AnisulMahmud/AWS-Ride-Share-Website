# AWS-Website
Website deploying in AWS

1. ArcGIS - for map
2. store/update/pull code - Github / CodeCOmmit- you can use github also- We took the code from this, aws s3 cp s3://wildrydes-[your_region_name, like us-west-2]/WebApplication/1_StaticWebHosting/website ./ --recursive
3. permission for the code -- IAM
4. hosting website and make updates -- You can use codeCommit or github and then connect that with Amplify to deploy your code, you can also changes something inside the code and check if amplify working with continuous development or not
5. User to register and log in - cognito [userPool] ( used to authentication)
6. ride sharing functionality
7. store.return ride results
8. invoke ride sharing functionality

![Alt text](image.png)
