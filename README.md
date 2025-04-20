# Elastic Agent Deployment Kit

This project provides simple scripts and automation to deploy [Elastic Agent](https://www.elastic.co/elastic-agent) on EC2 and EKS environments.

It includes:
- ✅ Install script for Linux-based EC2
- ✅ Fleet enrollment script with token-based auth
- 🛠️ Future: Terraform and Ansible-based deployment
- 🐳 Optional: EKS DaemonSet configuration

---

## 💻 EC2 Quick Start

1. SSH into your Linux EC2 instance  
2. Run the installer:
```bash
curl -O https://raw.githubusercontent.com/YOUR_USERNAME/elastic-agent-deploy-kit/main/ec2/install_agent.sh
chmod +x install_agent.sh
./install_agent.sh
