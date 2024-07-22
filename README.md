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

