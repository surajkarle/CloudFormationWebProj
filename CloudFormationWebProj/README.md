# 🚀 AWS CloudFormation Static Website Project

This project deploys a **fully automated static website** on an EC2 instance using **AWS CloudFormation** and **Amazon Linux 2023**, inside a custom VPC.

---

### 👨‍💻 Project by: Suraj Karle  
📍 *Cloud Engineer in the making | Practicing Infrastructure as Code (IaC)*

---

## 🧱 Tech Stack

- **AWS CloudFormation** – Infrastructure as Code
- **Amazon EC2** – t2.micro, Amazon Linux 2023
- **VPC** – Custom VPC with subnet, route table, and Internet Gateway
- **Security Groups** – Allow HTTP (80) and SSH (22)
- **Apache HTTP Server** – For serving the static website

---

## 🌐 Architecture Overview

Client (Browser)
|
v
[Public EC2 Instance] <-- HTTP (port 80)
|
v
[VPC with Public Subnet + IGW]
|
v
[Internet Gateway] ---> Internet

yaml
Copy
Edit

---

## 🔧 What It Does

- Creates a custom VPC and subnet
- Sets up Internet Gateway and route table
- Launches EC2 instance in a public subnet
- Installs Apache (httpd)
- Deploys a modern, mobile-friendly static HTML page
- Displays your name (Suraj Karle) and a GitHub project link

---

## 🚀 How to Deploy

1. Upload `template.yaml` into AWS CloudFormation
2. Provide your KeyPair name when prompted
3. Wait for the stack to complete
4. Get the public IP from **Outputs** tab
5. Open it in browser — your website is live!

---

## 📌 Output Sample

```html
<h1>🚀 CloudFormation Static Site Deployed</h1>
<p>Hosted on EC2 inside a custom VPC.</p>
<p>Created by Suraj Karle</p>
🧑‍🎓 Learning Outcomes
Learned CloudFormation syntax

Bootstrapped EC2 with Apache

Created full-stack infrastructure as code

Solved real AWS errors (IAM, deletion, roles)

Built a hands-on project for your resume

🙋 About Me
Suraj Karle
Cloud Enthusiast | AWS Learner
GitHub
LinkedIn

🏷️ Tags
#AWS #CloudFormation #EC2 #VPC #DevOps #InfrastructureAsCode #SurajKarle #StaticWebsite #CloudProject

⭐ Star this project if you liked it. Fork it to learn more!