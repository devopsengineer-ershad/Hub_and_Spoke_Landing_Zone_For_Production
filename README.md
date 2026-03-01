# 🌍 Azure Hub & Spoke Landing Zone  
## 🚀 Enterprise Azure Infrastructure using Terraform

---

## ✨ About The Project

An **Enterprise-Grade Azure Landing Zone** implementing **Hub & Spoke Network Architecture** using a fully modular **Terraform framework**.

Built following **Microsoft Cloud Adoption Framework (CAF)** principles for secure and scalable cloud environments.

✅ Centralized Security  
✅ Private Workload Connectivity  
✅ Enterprise Network Segmentation  
✅ Scalable Platform Foundation  

---

## 🏗 Architecture Overview

🔹 Hub → Shared Connectivity & Security  
🔹 Spokes → Application Workloads  
🔹 Secure traffic routing via Firewall + UDR  

---

## ⚙️ Platform Capabilities

### 🌐 Networking
- Hub & Spoke Virtual Networks
- Subnet Segmentation
- VNet Peering
- User Defined Routing

### 🔐 Security
- Azure Firewall
- Bastion Secure Access
- Network Security Groups
- Azure Key Vault
- Private Endpoints

### 🖥 Compute & Data
- Azure Virtual Machines
- SQL Server & Database
- Load Balancer
- Application Gateway

### 📊 Monitoring
- Log Analytics Workspace
- Centralized Diagnostics

---

## 🚀 Deployment

Run the following Terraform commands to deploy the landing zone:

```bash
terraform init
terraform validate
terraform plan
terraform apply -auto-approve

📂 Repository Structure
Azure-Landing-Zone
│
├── Modules/
│   ├── Networking/
│   ├── Security/
│   ├── Compute/
│   └── Monitoring/
│
├── Environments/
│   └── Production/
│
└── main.tf
🎯 Key Highlights

✨ Enterprise Landing Zone Ready
🔒 Zero Trust Network Design
⚡ Modular & Reusable Terraform
🌍 Production Scale Architecture
📦 Hub-Level Shared Services

🧠 Use Case

✔ Enterprise Platform Engineering
✔ Multi-Tier Applications
✔ Secure Azure Foundations
✔ Dev / Test / Prod Isolation

👨‍💻 Author

Ershad Alam
💠 Azure DevOps Engineer | Terraform | Kubernetes
