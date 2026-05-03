nano README.md
# 🚀 Multi-Node Automation using Ansible

## 📌 Project Overview
This project demonstrates how to automate multiple Linux nodes using Ansible.

## 🖥️ Setup
- Ubuntu (Master Node)
- Linux Mint, Rocky Linux, CentOS (Worker Nodes)

## ⚙️ Features
- Static IP configuration
- Passwordless SSH setup
- Ansible inventory management
- Automated Nginx installation
- Custom web page deployment

## 🚀 Commands Used
```bash
ansible all -m ping
ansible all -m package -a "name=nginx state=present" --become
🌐 Output

Hello from Ansible
