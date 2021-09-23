# Serverless Invoice React App

Reference: https://github.com/CodeEngineTechnology/Serverless_Invoice_App

Followed tutorial to host a web app on aws. 

## AWS Architecture
* **S3**  : Host the React App 
* **API Gateway** : Route API calls from React App in S3 bucket to Lambda functions
* **Lambda Functions** : Retrieve data from DynamoDB and send back to client application
* **DynamoDB** : Database
* **IAM** : Give permissions to services


## Tech Stack
* **AWS** : Hosting serverless architecture
* **React**
* **Reactstrap** : Styled components such as tables and buttons
* **Bootstrap** : Style front end
* **Git** and **Github** : Version Control
* **Node.js** : Lambda scripting language

## To Do
* Create a from to add invoices
* Create post api resource to add invoice items to DynomoDB
* Create delete and edit api calls
* Add authentication


## Reflection

### Learning Outcomes
1. How to host React app on S3 bucket
2. How to route api calls through AWS API Gateway
3. Learned how to work with api's and transfering data in json format. Learning how to use fetch with api's
4. How to create lambda function written in node.js to fetch data from DynamoDB
5. How to create DynamoDB table
6. How to use IAM to give permissions
7. Testing AWS serverless API calls
8. Learned about asynchronous concepts such as promises, .then, async functions, await keyword
9. How to create RESTFUL API and support CRUD with get and post fetch calls. 


### Unexpected Obstacles
* It is more work to create lambda functions to handle backend api calls than have a monolithic Express.js backend

## Available Scripts

1. Clone repo
2. Run `npm install`
3. Run `npm start`

## Link:
http://invoice-processing-trucks.s3-website.us-east-2.amazonaws.com/


