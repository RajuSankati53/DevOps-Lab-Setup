# 🚀 DevOps Learning Lab Setup (GCP VM)

Welcome to my DevOps Learning Journey!  
This repository documents my step-by-step setup, tools installation, and practices as I master DevOps concepts hands-on.

---

## 🖥️ GCP VM Details

| Field | Value |
|:---|:---|
| Cloud Provider | Google Cloud Platform (GCP) |
| VM Type | e2-medium (2 vCPU, 4GB RAM) |
| Disk Size | 50 GB (Standard SSD) |
| OS | Ubuntu 22.04 LTS |
| Firewall Rules | Allow HTTP and HTTPS traffic |

---

## 🛠️ Installed Tools and Their Purpose

| Tool | Purpose | Official Documentation |
|:---|:---|:---|
| [Git](https://git-scm.com/doc) | Version control system to track code and collaborate on GitHub |
| [Docker](https://docs.docker.com/) | Build, run, and manage containers |
| [Terraform](https://developer.hashicorp.com/terraform/docs) | Infrastructure as Code to automate cloud resources |
| [Ansible](https://docs.ansible.com/) | Automate server setup and application deployments |
| [kubectl](https://kubernetes.io/docs/reference/kubectl/) | Command-line tool to manage Kubernetes clusters |
| [Helm](https://helm.sh/docs/) | Kubernetes package manager for easy application deployment |
| [Minikube](https://minikube.sigs.k8s.io/docs/) (Optional) | Local Kubernetes cluster for testing |

---

## 📋 Why We Are Installing These Tools

| Step | Why? |
|:---|:---|
| Update System Packages | Ensure security patches and latest versions before installing new software |
| Install Git | Clone repositories, push changes, manage versions of code |
| Install Docker | Run applications inside containers easily and portably |
| Install Terraform | Automate the creation of cloud servers, networking, databases |
| Install Ansible | Configure systems automatically (install apps, set settings) |
| Install kubectl | Manage Kubernetes clusters — deploy and troubleshoot apps |
| Install Helm | Deploy complex apps into Kubernetes easily (like Prometheus, Jenkins) |
| Install Minikube | (Optional) Create a local Kubernetes cluster inside the VM for practice |

---

## 🧰 Full Setup Commands (Ubuntu 22.04)

### Update System Packages
```bash
sudo apt update && sudo apt upgrade -y
