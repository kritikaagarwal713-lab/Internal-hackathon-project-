# Event-Driven E-Commerce Order Processing System

An AWS-based event-driven system for processing e-commerce orders asynchronously and reliably.

## 📌 About
E-commerce orders involve multiple operations such as payment, inventory, invoice, and notifications. Processing all these operations synchronously can be slow and difficult to scale.

This project uses an event-driven architecture to process orders asynchronously and independently using AWS services instead of handling all operations synchronously.

## ☁️ AWS Services
- API Gateway
- AWS Lambda
- Amazon SQS
- DynamoDB
- CloudWatch

## 🔄 Workflow

Customer → API Gateway → Lambda → SQS → Processing Lambda → DynamoDB

## 🚀 Key Features
- Asynchronous order processing
- Order status tracking
- Serverless architecture
- Independent processing of multiple orders
- Cloud monitoring
  
## 🛠️ Tech Stack

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![API Gateway](https://img.shields.io/badge/API%20Gateway-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![SQS](https://img.shields.io/badge/SQS-FF9900?style=for-the-badge&logo=amazonsqs&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF9900?style=for-the-badge&logo=amazoncloudwatch&logoColor=white)
