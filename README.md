# AWS EXPONENT ENGINE
Welcome to AWS Exponent Engine, a user-friendly web application for exponent computations.
## How It Works
* Users input base and exponent numbers into the provided form.
* Upon clicking "calculate," data is sent to the API Gateway endpoint.
* Lambda function performs the computation and stores the result in DynamoDB.
* The calculated result is returned to the user via a pop-up window.
## Key Features
* Simple HTML webpage interface hosted on AWS Amplify.
* Utilizes AWS Lambda function for efficient math calculations.
* API Gateway endpoint triggers Lambda function seamlessly.
*	DynamoDB integration is used to secure the storage of calculation results.
*	Enhanced user experience with results displayed in a pop-up window.
## ARCHITECTURAL DIAGRAM
![Architectural Diagram](https://github.com/Prathyushkv/gitpractice/blob/9255682151d0da54e5ab3d7acc396131bdbb81ab/AWS%20Exponent%20Engine.png)

## Here are the steps involved in building the web application:
1. Create and host a simple HTML webpage using Amplify
2. Create a Lambda function to do math calculations
3. Create an API Gateway endpoint to trigger the Lambda function
4.	Configure DynamoDB to store the results of the calculations
5.	Set up permissions so that the Lambda function has permission to write to the DynamoDB table
6.	Update the HTML webpage to call the API Gateway endpoint
7.	Deploy the updated HTML webpage to Amplify
8.	Once the web application is complete, users can enter two numbers into a form on the webpage. When they click the calculate button, the numbers are sent to the API Gateway endpoint, which triggers the Lambda function. The Lambda function does the calculation and stores the result in the DynamoDB table. The result is then returned to the user in a pop-up window.
## Step 1: Creating and hosting a web page
1.	Choose AWS Amplify: Opt for AWS Amplify for creating and hosting the web page, as it offers a straightforward solution.
2.	Create HTML Page Locally: Develop a simple HTML page using a text editor on your local machine.
3.	Save HTML File: Save the HTML file with the name "index.html" (or any preferred name) on your local machine.
Index.html code:
```<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>To the Power of Math!</title>
</head>

<body>
    To the Power of Math!
</body>
</html>
```
4.	Zip HTML File: Compress the HTML file into a ZIP folder. Ensure that only the HTML file is included in the ZIP folder.
5.	Access AWS Console: Log in to the AWS console.
6.	Navigate to Amplify: Go to the Amplify service in the AWS console.
7.	Create a New App: Create a new app within Amplify.
8.	Select Hosting Option: Choose the option to host a web app without a Git provider.
9.	Name the App: Provide a name for the app, e.g., "Power of Math".
10.	Choose Environment: Select the environment, such as "dev".
11.	Upload ZIP File: Upload the ZIP folder containing the HTML file to Amplify.
12.	Save and Deploy: Save the configuration and deploy the app.
13.	Wait for Deployment: Allow some time for the deployment process to complete.
14.	Access Deployment Link: Once deployed successfully, access the deployed web page using the provided link.
15.	Verify Web Page: Verify that the web page is live and accessible through the provided link.
    We now have a live web page that users can navigate to.



