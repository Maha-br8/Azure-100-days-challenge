# Day 01: Deploy a Web Application on Azure VM

## ✅ Goal
Deploy a static HTML web page using Apache on a Linux Azure VM.

# Day 01: Deploy a Web Application on Azure VM

## 🎯 Objective

Deploy a static HTML website using Apache on a Linux-based Azure Virtual Machine.

---

## 🔧 Steps Followed

1. **Created an Azure VM** via Azure Portal (Ubuntu OS)
2. **Configured Inbound Rule** for port `80` (HTTP) in the NSG
3. **Connected to VM** using Azure Cloud Shell:
   ```bash
   ssh azureuser@<public-ip>
