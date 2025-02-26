# Deploying a Simple Static Website on AWS Elastic Beanstalk 🚀  

## Description  
This project is a **basic "Hello, World!" web application** deployed on **Amazon Web Services (AWS) Elastic Beanstalk**. It consists of a simple **HTML file** with styling from **CSS**, demonstrating how to deploy a static website using AWS.  

## Features  
- ✅ Simple static HTML & CSS webpage deployment  
- ✅ Hosted on AWS Elastic Beanstalk  
- ✅ Scalable and easy to manage  

## Prerequisites  
Before deploying, ensure you have:  
- An **AWS account**  
- Installed **AWS CLI** and **Elastic Beanstalk CLI (EB CLI)**  
- Configured AWS credentials (`aws configure`)  
- **HTML and CSS files** for the website  

## Deployment Steps  

### 1️⃣ Install AWS Elastic Beanstalk CLI  
```sh  
pip install awsebcli --upgrade --user  

#### 2️⃣ Initialize Elastic Beanstalk Project
```sh
eb init -p static my-static-site  

#### 3️⃣ Create an Environment
```sh
eb create my-env  


### 4️⃣ Deploy Application
```sh
eb deploy  

###  Open the Application in a Browser
```sh
eb open  

### Project Structure
├── index.html   # Main HTML file
├── style.css    # CSS file for styling
├── README.md    # This file

