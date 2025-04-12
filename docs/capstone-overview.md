
# 🏦 Capstone Project Overview: Know Your Customer (KYC) Application

## 📘 Project Context

This project is developed as part of the AWS Cloud Foundations program at Amazon Cloud Institute (ACI). It represents a real-world scenario where a fictional financial institution—AnyCompany Bank—builds a serverless application on AWS to streamline customer onboarding.

The goal is to automate and secure the process of collecting and validating customer information, improving both compliance and user experience.

---

## 🎯 Project Objective

To build a backend cloud-native solution using AWS that performs the following tasks:

- Accepts a CSV file containing customer application information
- Accepts a selfie photo and a driver's license image
- Extracts text from the license using Amazon Textract
- Compares the selfie and license photos using Amazon Rekognition
- Validates license data against a third-party API
- Stores results and statuses in DynamoDB
- Uses serverless tools (Lambda, API Gateway, SNS, SQS) for scalability

---

## 🔧 AWS Services Used

- **Amazon S3** – Store uploaded documents
- **AWS Lambda** – Orchestrate logic and validation steps
- **Amazon Rekognition** – Face comparison
- **Amazon Textract** – Text extraction from ID
- **Amazon API Gateway** – Connect with third-party API
- **Amazon DynamoDB** – Persist onboarding results
- **SNS & SQS** – Asynchronous communication
- **IAM Roles** – Secure access policies

---

## 📅 Development Plan

The application will be built in 10 weekly labs. Each lab introduces one or more AWS services and builds toward the complete KYC application.

---

## 🧠 Expected Outcomes

By the end of this capstone, the application will:
- Demonstrate how to build secure, scalable onboarding solutions
- Highlight the power of AI/ML services for document processing
- Show proficiency in using IAM, S3, Lambda, and other core AWS tools

---

## 👤 Author

Carlos Manuel Cordova Ortiz  
Cloud Developer – ACI Capstone Project  
[LinkedIn](https://www.linkedin.com/in/carloscordovadev)
