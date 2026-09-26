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

[![AWS](https://img.shields.io/badge/AWS-Cloud-orange)](https://aws.amazon.com/)
[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)
[![API Gateway](https://img.shields.io/badge/API-Gateway-orange)](https://aws.amazon.com/api-gateway/)
[![Lambda](https://img.shields.io/badge/Lambda-orange)](https://aws.amazon.com/lambda/)
[![SQS](https://img.shields.io/badge/SQS-orange)](https://aws.amazon.com/sqs/)
[![DynamoDB](https://img.shields.io/badge/DynamoDB-orange)](https://aws.amazon.com/dynamodb/)
[![CloudWatch](https://img.shields.io/badge/CloudWatch-orange)](https://aws.amazon.com/cloudwatch/)
