# Day 2 – MySQL on Azure VM

## ✅ Goals
- Set up MySQL on an Azure VM
- Allow remote access via port 3306
- Automate backups
- Upload to Azure Blob Storage

## 💻 Tools Used
- Azure CLI
- MySQL Server on Ubuntu VM
- Cron jobs
- Azure Storage Blob

## 📘 Summary
I created an Ubuntu VM on Azure using the CLI, installed MySQL, configured a remote-accessible user, opened required ports, wrote a backup script, and automated daily backups using cron. These backups are uploaded to Azure Blob Storage.

Since this was done on a free trial, resources will be deleted — but the process is fully documented here.

