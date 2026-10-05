# 🔐 CloudVault – Cloud Password Manager

A modern and user-friendly **Cloud Password Manager** designed to help users organize and manage their login credentials from a single dashboard.

> ⚠️ **Educational Prototype:** This version is created for academic purposes. It stores demonstration data using browser LocalStorage and does not provide production-grade password encryption.

## 📌 About the Project

CloudVault is a password-management web application that allows users to store, search, manage, and generate passwords for different websites and applications.

The project demonstrates important concepts related to **web development, password management, authentication, data storage, and cloud computing**.

## ✨ Features

* 🔐 Password management dashboard
* ➕ Add new account credentials
* 👁️ Show and hide passwords
* 📋 Copy passwords
* 🗑️ Delete saved accounts
* 🔎 Search websites and usernames
* 🏷️ Categorize accounts
* 🔑 Generate strong passwords
* 📊 Password security score
* 📱 Responsive user interface
* 💾 Browser LocalStorage for prototype data

## 🗂️ Categories

The application supports:

* 📱 Social Media
* 💼 Work
* 🎓 Education
* 🛒 Shopping

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Prototype Storage

* Browser LocalStorage

### Planned Cloud Technologies

* Amazon Cognito
* AWS Lambda
* Amazon API Gateway
* Amazon DynamoDB
* AWS Key Management Service (KMS)
* Amazon S3

## ☁️ Proposed Cloud Architecture

```text
              User
                │
                ▼
       Web Application
         HTML/CSS/JS
                │
                ▼
        Amazon Cognito
       Authentication
                │
                ▼
          API Gateway
                │
                ▼
          AWS Lambda
                │
                ▼
           DynamoDB
        Encrypted Data
```

## 🔐 Security Concept

A production version of this application should use proper cryptographic encryption and secure key management.

The planned cloud version would use:

* User authentication
* Encryption at rest
* Encryption in transit
* Secure API access
* User-specific database access
* AWS KMS for key management
* Strong password generation
* No plain-text password storage

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/cloud-password-manager.git
```

### 2. Open the project

Open the project folder using **Visual Studio Code**.

### 3. Run the application

Open `index.html` using:

* VS Code Live Server
* Google Chrome
* Microsoft Edge
* Any modern web browser

## 📂 Project Structure

```text
Cloud-Password-Manager/
│
├── index.html
└── README.md
```

## 🔮 Future Enhancements

* ☁️ AWS cloud integration
* 🔐 Amazon Cognito authentication
* 🗄️ DynamoDB database
* 🔒 Proper client-side encryption
* 🔑 Secure key management using AWS KMS
* 👤 Individual user accounts
* 📊 Advanced security dashboard
* 🚨 Weak-password alerts
* 🔄 Password update reminders
* 🌐 Secure cloud synchronization
* 📱 Mobile-friendly interface

## 🎯 Project Objective

The objective of CloudVault is to demonstrate how a password-management application can be designed using modern web technologies and extended into a secure cloud-based architecture.

## 👩‍💻 Developed By

**Charulatha S**

B.E. Computer Science Engineering
Prathyusha Engineering College

## 📄 License

This project is created for **educational and academic purposes**.
