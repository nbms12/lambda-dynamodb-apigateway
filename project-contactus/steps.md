Aim: Deploy web application ( email submission form )  with Lambda, ApiGateway and DynamoDB.

services used : DynamoDB, aws lambda , API gateway. 

step1: create a function ( type: rest API ) which has   GET POST methods. 

step2: create a role , access to dynamo db, api gateway.

![image](https://github.com/user-attachments/assets/732916f6-bf9e-4b4a-9ad7-27e1fc7249f6)

step3: create a table name "manjutable" with email( string )  as primary key 

step4: create a methods called get and post method , enable Lambda proxy integration.

step5: deploy api and new stage called dev , and copy invoke URL 

![image](https://github.com/user-attachments/assets/23e0ea7e-3dd3-4ba5-ae38-4b9b897a1e5a)

step6: add table name and deploy lambda function 

step7: open invoke url and fields data and submit .

![image](https://github.com/user-attachments/assets/acb17dd8-65a5-4e04-8917-b249ca3da712)


step8: verify data in dynamo DB . 

![image](https://github.com/user-attachments/assets/a9e4dc2b-7d4f-4cf3-b398-54d26d8fea32)
