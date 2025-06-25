## AWS AI Stack - Serverless AI Application Boilerplate

AWS AI Stack is a ready-to-use, full-stack boilerplate for building serverless AI applications on AWS. This project provides a solid AWS foundation, allowing developers to integrate AI models via AWS Bedrock while ensuring data privacy and separation from model providers.

## 🚀 Features

### 🏗️ Full-Stack Architecture

### Backend:

API Gateway V2

AWS Lambda (Serverless functions)

AWS EventBridge (Event-driven architecture)

AWS DynamoDB (NoSQL Database)

AWS Bedrock (AI models)

### Frontend:

Vanilla React application

### 🤖 AI Chat & Streaming Responses

Fully serverless AI chatbot architecture

Streaming responses for real-time AI interactions on AWS Lambda

Integrates multiple AI models via AWS Bedrock (Claude 3.5 Sonnet, Llama 3.1, Mistral Large 2, etc.)

Ensures data privacy—your app data never leaves AWS

### 💰 100% Serverless

Auto-scaling without paying for idle time

Pay-per-use model (additional costs may apply for DynamoDB and AWS Bedrock-trained models)

### 🌐 Custom Domain Names

API Gateway services configured with serverless-domain-manager plugin

Lambda services configured with CloudFront Distributions

📡 API & Event-Driven Architecture

Express.js API for custom business logic

Shared EventBridge for publishing & subscribing to events

Worker service for processing events asynchronously

### 🔐 Built-In Authentication

API Gateway authorizer for secured endpoints

User login & registration using Lambda (Express.js) + DynamoDB

JWT token authentication for session management

### 🏗️ Multi-Environment Support

Shared configuration for all services

Separated configurations for different environments (dev, prod, etc.)

### 📦 Domain-Oriented Architecture

Modular components for easy customization (remove AI Chat, authentication, etc., if not needed)

### 🔄 CI/CD with GitHub Actions

Deploy services to production via GitHub Actions

Deploy PR environments and auto-remove services after merge

## ScreenShots

### SignUp

![image](https://github.com/user-attachments/assets/c924bf8c-9e3f-4345-af46-98c29f7375b3)

### Login

![image](https://github.com/user-attachments/assets/a27164d3-0522-4a45-b1e4-814174ca1f02)

### Home

![image](https://github.com/user-attachments/assets/d6d86a7c-2649-4fbf-a32c-803debbc6546)

## 🛠️ Installation & Setup

### Clone the Repository

git clone https://github.com/your-username/aws-ai-stack.git
cd aws-ai-stack

### Install Dependencies

npm install

### Configure AWS Credentials

### Ensure you have the AWS CLI installed and configured:

aws configure

### Deploy to AWS

npx serverless deploy

### Start the Frontend

cd frontend
npm start

## 📜 License

This project is open-source and available under the MIT License.
