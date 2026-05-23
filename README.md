# AWS Portfolio Website

A full-stack cloud portfolio website built and deployed on AWS.

## Architecture

- **EC2** — Web server hosting the application
- **Application Load Balancer** — Distributes traffic across servers
- **Auto Scaling Group** — Automatically scales based on demand
- **CloudFront** — Global content delivery network
- **Route 53** — DNS management
- **Lambda** — Serverless microservices
- **API Gateway** — REST API for blog microservice
- **DynamoDB** — NoSQL database for storing data
- **S3** — Static file storage
- **CloudFormation** — Infrastructure as code
- **IAM** — Security and access management

## Microservices

- **View Counter** — Tracks website visits
- **Contact Form** — Handles user messages
- **AWS Latest News** — Fetches and displays latest AWS news
- **Blog** — Create and display blog posts

## What I Learned

- Deploying and configuring EC2 instances
- Setting up secure access with IAM roles and SSM
- Building serverless microservices with Lambda
- Connecting services using API Gateway and Function URLs
- Debugging CORS issues and permission errors
- Infrastructure as Code using CloudFormation
