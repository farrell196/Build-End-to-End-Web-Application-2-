# Build a Full End-to-End Web Application with 7 Service


## TL;DR
Build a ride sharing app, pulling from the AWS Wild Rydes sample project. Use CodeCommit to store/update/pull code and also IAM to handle permissions. After this I needed a place to host website and make update (Amplify). I now needed another way for users to register & login user (Cognito). I used Lambda and DynamoDB needed a way to do ride sharing functionailty and somewhere to store/return ride sharing. I used API Gateway to invoke ride sharing functionality. 

## Ride Sharing App
A transportation service App.  The user clicks signs in/register to be able to access the app which they would know be able to allow or deny access to locate where they are to be able to place a ride. 

The App consists of HTML, CSS and JavaScript.

OTHER SERVICES:
-  ArcGIS (GPS Service)

## The Deployment Environment
The code will be deployed and hosted in S3.


