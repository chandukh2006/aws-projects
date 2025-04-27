# 🚀 AWS VPC Infrastructure Project (Manual Setup)

Welcome to my Real-Time DevOps Project —  
This project simulates a real-world production environment where infrastructure is manually created in AWS — without Terraform or IaC tools — to demonstrate deep understanding of AWS Services and Networking fundamentals.

---

## 🛠️ Architecture Overview

- 🔹 **Virtual Private Cloud (VPC)** with two Availability Zones (AZs)
- 🔹 **Public Subnets** for Bastion Host and Load Balancer
- 🔹 **Private Subnets** for Application Servers
- 🔹 **Bastion Host** (EC2) for SSH into private instances
- 🔹 **Application Load Balancer (ALB)** exposing backend servers
- 🔹 **Auto Scaling Group (ASG)** managing application servers
- 🔹 **Target Groups** routing traffic to healthy instances
- 🔹 **NAT Gateways** enabling outgoing internet traffic for private instances
- 🔹 **Security Groups** to control secure access

> ✅ Entire setup is done manually via AWS Console to ensure complete understanding of service interconnections and networking principles.

---

## 📈 Project Architecture Diagram

![AWS VPC Architecture](./architecture.png)

> (Upload your AWS Architecture image here and update the image path if needed.)

---

## 🧩 Services Used

| AWS Service | Purpose |
| :--- | :--- |
| VPC | Isolated network environment |
| EC2 | Virtual servers (Bastion Host, Application Servers) |
| Auto Scaling Group | Manage EC2 instance fleet automatically |
| Application Load Balancer | Distribute incoming traffic |
| NAT Gateway | Internet access for private subnets |
| IAM | Security and access control |
| CloudWatch | Monitoring and alerting |
| Security Groups | Firewall rules for secure access |

---

## 📋 What I Learned

- 🌐 Building secure VPC architectures with public and private subnets.
- 🔒 Configuring Bastion Hosts for secure access to private EC2 instances.
- 🛡️ Designing Security Group rules and setting up NAT Gateways.
- ⚙️ Implementing Auto Scaling Groups for fault tolerance and scalability.
- 🚀 Setting up Application Load Balancers with Target Groups and Health Checks.
- 🛠️ Manual setup without automation — true AWS service integration knowledge.

---

## 🎯 Why This Project Matters

This project showcases **hands-on AWS skills**, **network design capabilities**, and the **ability to think like a real-world DevOps/Cloud Engineer** designing production-grade architecture.

---

## 📎 Future Scope

- ➡️ Terraform or CloudFormation template conversion
- ➡️ CI/CD integration to automate application deployments
- ➡️ Monitoring improvements with Prometheus and Grafana
- ➡️ Implementing Disaster Recovery strategies across regions

---

# 🌟 Thank You!

If you found this project interesting, feel free to ⭐ star the repo or connect with me!

---

## 🚀 Quick Summary

> This is not just a project — it’s a real proof of manual AWS networking, security, scaling, and architecture skills that a DevOps/Cloud Engineer must master.

---

# 🏷️ Tags

`#AWS` `#DevOps` `#CloudEngineering` `#VPC` `#EC2` `#AutoScaling` `#LoadBalancer` `#ManualSetup` `#RealWorldProject`
