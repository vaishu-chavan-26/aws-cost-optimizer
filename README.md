# 🚀 Automated AWS Cost Optimizer

![AWS](https://img.shields.io/badge/AWS-Lambda-orange)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Overview
This project automatically reduces AWS costs by identifying and stopping idle EC2 instances using a fully serverless architecture.

---

## 🧰 Technologies Used
- AWS Lambda  
- Amazon EC2  
- Amazon CloudWatch  
- Amazon EventBridge  
- Python (boto3)  

---

## ⚙️ How It Works
1. Lambda function fetches all EC2 instances  
2. Retrieves CPU utilization from CloudWatch  
3. If CPU usage < 10%, instance is stopped  
4. EventBridge triggers the function daily  

---

## 🏗️ Architecture
![Architecture](screenshots/architecture.png)
---

## 📊 Output Screenshots

### 🖥️ EC2 Instance Stopped
![EC2](screenshots/ec2-stopped.png)

### ⚡ Lambda Execution
![Lambda](screenshots/lambda-execution.png)

### 📈 CloudWatch Logs
![Logs](screenshots/logs.png)

### ⏰ EventBridge Rule
![EventBridge](screenshots/eventbridge.png)

---

## ✨ Features
- Automated cost optimization  
- Serverless architecture  
- Scalable and efficient  
- Real-time monitoring using CloudWatch logs  

---

## 🚀 Future Improvements
- Tag-based instance filtering  
- Email alerts using SNS  
- Multi-region support  

---

## 💡 Key Learning
- Implemented serverless automation using AWS Lambda  
- Integrated CloudWatch metrics for decision-making  
- Used EventBridge for scheduling tasks  
- Hands-on experience with boto3 and AWS services  

---

## 👩‍💻 Author
**Vaishnavi Chavan**
