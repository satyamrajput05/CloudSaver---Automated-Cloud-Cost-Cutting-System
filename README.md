# CloudSaver:-Automated-Cloud-Cost-Cutting-System

CloudSaver is an automated monitoring system that helps reduce unnecessary cloud costs by detecting underutilized EC2 instances and stopping them. This system is ideal for students, startups, or organizations trying to optimize AWS infrastructure costs.

🚀 Features
- **AWS EC2 Monitoring** via CloudWatch
- **Automated Instance Shutdown** using AWS Lambda
- **API Access** using API Gateway
- **Trigger on Low CPU Usage**

🛠️ Tech Stack
- AWS EC2
- AWS Lambda (Python)
- AWS CloudWatch
- AWS API Gateway
- IAM Roles
- GitHub for version control
 
📸 Screenshots (Uploaded in repo folder `/screenshots`)
1. EC2 Instance running
2. Lambda Function setup
3. CloudWatch Alarm
4. API Gateway configuration
5. Logs Insights (optional)


📦 Folder Structure
CloudSaver/
├── lambda_function.py
├── requirements.txt
├── screenshots/
│   ├── ec2_instance.png
│   ├── lambda_config.png
│   ├── cloudwatch_alarm.png
│   ├── api_gateway.png
│   └── ...
├── architecture.png
└── README.md

📌 How It Works
1. EC2 Instance is launched.
2. CloudWatch tracks CPU utilization.
3. If CPU usage < 1% (customizable), it triggers a CloudWatch Alarm.
4. Alarm invokes Lambda Function.
5. Lambda stops the EC2 instance and logs the event.
🌐 API Gateway URL
https://r1v9apn3tc.execute-api.eu-north-1.amazonaws.com/CloudSaverStage
You can call this endpoint to manually invoke the Lambda for testing.

🧠 Future Enhancements
- GUI Dashboard
- Email Alerts
- Resource Usage Charts
- Pro version with Flask + React.js frontend

## 🙌 Made With
AWS ❤️ | Python 🐍 | Cloud Enthusiasm ☁️

## 👨‍💻 Developer
**Satyam Rajput**
- Email: satyamrajput21304@gmail.com


