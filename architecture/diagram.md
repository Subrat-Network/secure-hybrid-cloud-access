# 🌐 Cloud Architecture Diagram

## 📌 Overview

This project demonstrates a secure hybrid cloud architecture using Azure and AWS. The design focuses on controlling access, securing network traffic, and monitoring activity.

---

## 🧠 Architecture Flow

```
User (Trusted IP)
        ↓
     Internet
        ↓
-----------------------------------------
|                                       |
Azure (VNet)                      AWS (VPC)
|                                       |
NSG                              Security Group
|                                       |
VM                               EC2 Instance
|                                       |
Azure Monitor                    CloudWatch

## 🔐 Security Components

### Azure

* Virtual Network (VNet)
* Network Security Group (NSG)
* Virtual Machine (VM)

### AWS

* Virtual Private Cloud (VPC)
* Security Groups
* EC2 Instance

---

## 🔥 Security Controls

* Allow access only from trusted IP
* Restrict ports (SSH/HTTPS)
* Deny all unnecessary traffic
* Apply least privilege using IAM

---

## 📊 Monitoring

* Azure Monitor for logs and alerts
* AWS CloudWatch for activity tracking

---

## 🎯 Key Learning

* Network security implementation in cloud
* Access control using NSG & Security Groups
* Real-world monitoring and threat detection

---

## 📸 Diagram

(Add architecture diagram image in screenshots folder)
