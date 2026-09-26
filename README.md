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
*AWS | Python | API Gateway | Lambda | SQS | DynamoDB | CloudWatch*
