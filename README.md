# azure-terraform-linux-vm
End-to-end Azure Linux VM deployment using Terraform (Infrastructure as Code), built from scratch via local PowerShell and compliant with Azure Policy tagging.
# Azure Terraform Linux VM Deployment

## 📌 Overview
This project demonstrates an end-to-end **Azure Infrastructure as Code (IaC)** deployment using **Terraform**, executed **entirely from scratch using local PowerShell**.

The solution provisions a fully functional **Linux Virtual Machine in Microsoft Azure**, including networking, security, public access, and policy-compliant tagging.

This lab was built to reflect **real-world enterprise Azure standards**, including Azure Policy enforcement and secure access via SSH.

---

## 🧱 Architecture Components
The infrastructure includes:

- Azure Resource Group
- Virtual Network (VNet)
- Subnet
- Network Security Group (NSG) with SSH access
- Public IP (Standard SKU, Static)
- Network Interface (NIC)
- Ubuntu Linux Virtual Machine
- Azure Policy-compliant resource tagging

All resources are deployed declaratively using Terraform.

---

## 🔧 Technologies Used
- **Terraform**
- **Microsoft Azure**
- **Azure CLI**
- **PowerShell (local)**
- **Linux (Ubuntu 20.04)**
- **SSH Key Authentication**

---

## 🛠️ What This Project Demonstrates
- Writing Terraform configurations from scratch
- Provider configuration and authentication
- Azure Policy compliance via mandatory tagging
- Resource dependency management
- Secure Linux VM provisioning with SSH
- Debugging and resolving real-world Azure/Terraform errors
- Running Terraform locally (not Cloud Shell)

---

## 🚀 How to Deploy

### Prerequisites
- Azure subscription
- Terraform installed locally
- Azure CLI installed
- Logged in via `az login`

### Steps
```bash
terraform init
terraform plan
terraform apply
