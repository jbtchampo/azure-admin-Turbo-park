# Azure Administrator Capstone Project: Turbo Park LLC

This project simulates a secure cloud migration for a growing transportation and logistics company, **Turbo Park LLC**.

---

## Project Summary

This project demonstrates the deployment, configuration, and management of a secure, scalable, and cost-effective Azure infrastructure. It includes components for identity, compute, networking, storage, automation, security, and monitoring — all modeled as a real-world IT migration scenario for Turbo Park LLC.

---

## 🧱 Tech Stack

- **Azure Active Directory**
- **Azure Virtual Network / NSGs / Bastion**
- **Azure Virtual Machines & Load Balancer**
- **Azure Blob & File Storage**
- **Azure Monitor & Automation**
- **Azure Key Vault & Defender for Cloud**

---

## 🗂️ Project Structure
📁 turbo-park-cloud-infra
├── identity/
│ └── aad_setup.md
├── compute-network/
│ ├── vm_deployment.ps1
│ ├── nsg_config.json
│ └── bastion_setup.md
├── storage/
│ ├── blob_lifecycle_policy.json
│ └── azcopy_script.sh
├── automation-monitoring/
│ ├── auto_shutdown_runbook.ps1
│ └── alert_rules.json
├── security/
│ ├── keyvault_policy.md
│ └── defender_report.pdf
├── architecture/
│ └── turbo_park_diagram.png
├── presentation/
│ └── project_summary.pptx
└── README.md

yaml
Copy
Edit

---

## 🧩 Modules

### 1️⃣ Identity & Access
- Created Azure Active Directory tenant for Turbo Park LLC
- Enabled MFA and Conditional Access for all staff logins
- Configured Privileged Identity Management (PIM) and RBAC

### 2️⃣ Compute & Networking
- Deployed VMs for dispatch systems and customer portals
- Set up Bastion for secure administrator access
- Load Balancer added for high-availability public web services

### 3️⃣ Storage & Backup
- Configured Blob and File Storage for logs and contracts
- Lifecycle management for cold storage of long-term files
- Enabled backup for compute workloads and shared files

### 4️⃣ Automation & Monitoring
- Automated VM shutdown after business hours
- Alerts for high CPU usage and security policy violations
- Dashboards and Log Analytics workspaces configured

### 5️⃣ Security & Cost
- Defender for Cloud enabled with baseline recommendations
- Key Vault used for encrypting API keys and internal secrets
- Enforced tagging policies and cost budgets via Azure Policy

---

## 📸 Screenshots & Diagrams

All screenshots and architecture diagrams related to Turbo Park LLC’s cloud infrastructure are in `/architecture`.

---

## 🧠 Lessons Learned

- Hands-on Azure Active Directory & secure access workflows
- Real-world scenario of deploying VM-based apps in subnets
- Built scalable, cost-optimized, and secure cloud infrastructure
- Configured automation for improved cloud governance

---

## 📅 Timeline

| Week | Focus Area                |
|------|---------------------------|
| 1    | Identity + Compute        |
| 2    | Networking + Storage      |
| 3    | Automation + Monitoring   |
| 4    | Security + Docs & Review  |

---

## 🧪 How to Reproduce

> 💡 Ensure you have an Azure subscription or free trial.

1. Clone this repo
2. Follow each module in the folders
3. Deploy components using Azure CLI, PowerShell, or Azure Portal
4. Collect screenshots and logs as project evidence

---

## 📫 Contact

Feel free to reach out via [LinkedIn](www.linkedin.com/in/jeanberlintchampo1) or open an issue if you'd like to collaborate or share feedback!

---

## 🔐 Disclaimer

This project is for educational purposes only. No customer or employee data from Turbo Park.
