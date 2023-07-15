# Serverless Web Application for Unicorn rides!

This is a simple serverless web application that enables users to request unicorn rides.   

The application will present users with an HTML-based user interface for indicating the location where they would like to be picked up and will interact with a RESTful web service on the backend to submit the request and dispatch a nearby unicorn.   

The application will also provide facilities for users to register with the service and log in before requesting rides.
   
   
  
  
# Application Architecture:
1.  AWS Amplify provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser.
2.  JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway.
3.  Amazon Cognito provides user management and authentication functions to secure the backend API.
4.  DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.
