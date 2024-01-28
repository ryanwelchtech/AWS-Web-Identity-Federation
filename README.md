# AWS-Web-Identity-Federation-Demo
In this advanced demo, I implemented a simple serverless application which uses Web Identity Federation hosted on the AWS platform. The application runs from a browser, gets the user to login using a Google ID and then loads all images from a private S3 bucket into a browser using presignedURLs.
## Tech Stack

- AWS S3 bucket for front-end application hosting.
- Google API Project as an ID Provider.
- Cognito and IAM Roles to swap Google Token for AWS credentials.

## Documentation

[AWS Cognito Web Identity Federation demo documentation can be found here.](https://github.com/acantril/learn-cantrill-io-labs/tree/master/aws-cognito-web-identity-federation)


## Authors

[@acantril](https://www.github.com/acantril) is the wonderful creator of the lab I followed along. Be sure to check him out!


## Demo

The demo can be accessed here https://d3fkp9owfo6oxp.cloudfront.net. Please refer to the screenshots below if the demo link is no longer accessible.



## Screenshots

![Unauthenticated view](https://i.imgur.com/L8X67dc.png)
![Google SSO Window](https://i.imgur.com/gQzWydN.png)
![Authenticated view](https://i.imgur.com/EJ6UKMk.png)


## Feedback

If you have any feedback, please reach out to me at ryanwelch.nsa@gmail.com.

