# CI/CD Pipeline with Jenkins, Ansible, Docker, and AWS with GitHub 🚀
##  📌 Description
This project automates the deployment process using **Jenkins, Ansible, Docker, and GitHub Webhooks** on **AWS**.  
It ensures seamless **continuous integration and deployment (CI/CD)**, making the process **faster, scalable, and reliable**.

## 🛠Technologies
- **Jenkins** → CI/CD automation
- **Ansible** → Configuration management & deployment
- **Docker** → Containerization for portability
- **GitHub Webhooks** → Automates pipeline triggering
- **AWS** → Cloud hosting for scalability
  
## 🔄 CI/CD Workflow
- 1️⃣ **GitHub Webhook triggers Jenkins** when a new commit is pushed.
- 2️⃣ **Jenkins pulls the latest code** and runs tests/builds.
- 3️⃣ **Ansible ensures infrastructure is configured** before deployment.
- 4️⃣ **Docker containerizes the application** for portability. 
- 5️⃣ **The final container is deployed on AWS**, ensuring high availability.
     
## ✨ Key Features
- ✔ **Automated builds & deployments** – No manual intervention needed.
- ✔ **Infrastructure as Code (IaC)** – Using Ansible for server configuration.
- ✔ **Scalability** – The project is cloud-ready with AWS integration.
- ✔ **Webhook-triggered CI/CD** – Faster release cycles with automated GitHub commits.

## ✨ Future Improvements
- ✔ Terraform (IaC) – Automate AWS resource provisioning.
- ✔ Prometheus & Grafana – Real-time monitoring of Jenkins, Docker, and AWS.
- ✔ Ansible Vault – Securely store sensitive credentials and enhance
  

## Walk-through:

 ![First try](https://github.com/Vlad774/website-for-pipeline/blob/main/screens/diagramm.png) 
 ![First try](https://github.com/Vlad774/website-for-pipeline/blob/main/screens/ec2-servers.png) 
 ![First try](https://github.com/Vlad774/website-for-pipeline/blob/main/screens/ansible_screen.png)
 ![First try](https://github.com/Vlad774/website-for-pipeline/blob/main/screens/docker_images.png)
 ![First try](https://github.com/Vlad774/website-for-pipeline/blob/main/screens/builds.png)
 ![First try](https://github.com/Vlad774/website-for-pipeline/blob/main/screens/pipeline%20is%20running.png)
