# 🌐 100 Days of Azure – Day 3

## 🚀 Goal
Set up and host a complete development environment on an Azure Virtual Machine using `code-server` (VS Code in the browser).

## 📝 What I Did
- ✅Created a new Ubuntu VM on Azure
- ✅ Set up SSH access using my local `.ssh` key pair
- ✅ Installed `code-server` (VS Code in the browser)
- ✅ Configured a secure password for web-based access
- ✅ Opened the necessary port (8080) in the Network Security Group (NSG)
- ✅ Accessed the VS Code environment from my browser via `http://<vm-public-ip>:8080`
- ✅ Understd the difference between code-server vs traditional RDP/SSH-based development
- ✅ Learned the advantages of browser-based development environments

## 🔧 Technologies Used
- **Azure Virtual Machine (Ubuntu)**
- **code-server (VS Code in browser)**
- **SSH for secure VM access**
- **Azure Network Security Groups (NSG)**
- **Git** for pushing code to GitHub

## 🔒 Security Notes
- Ensured that only port `8080` is open for HTTP access.
- Authentication is enabled using a password from `config.yaml`.
- VM can be shut down or deleted to preserve free-tier credits after use.

## 💡 Learnings
- A cloud-based dev environment like `code-server` is super helpful for remote, lightweight development.
- Makes it easy to switch devices and still work in the same environment.
- Bastion is secure but not necessary for daily development if `code-server` is properly secured.

## 📤 Next Step
✅ Pushed Day 3 progress to GitHub  
🔜 Moving on to Day 4: TBD

## 📅 Challenge Progress
- [x] Day 1 – Azure Fundamentals
- [x] Day 2 – Azure CLI & Resource Groups
- [x] Day 3 – Host Dev Environment on Azure VM
_

