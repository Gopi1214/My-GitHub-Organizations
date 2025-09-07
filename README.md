# 🛠️ RoboShop — Personal DevOps & SRE Project

This is a self-driven project that replicates the kind of infrastructure and automation challenges faced in real-world production environments. I designed, built, and deployed a complete e-commerce application and its underlying infrastructure using tools like **Terraform, Jenkins, Kubernetes, Docker, and AWS**.

---

## 📦 Project Summary

| Category             | Details                                                                 |
|----------------------|-------------------------------------------------------------------------|
| Type                 | **Personal Project**                                                    |
| Focus                | Full DevOps Lifecycle: Infra + App Deployment                           |
| Duration             | 2023–2025 (Ongoing improvements)                                        |
| Purpose              | Hands-on mastery of SRE & DevOps tools via a production-style setup     |
| Status               | ✅ Actively maintained                                                  |

---

## 🧱 Project Structure

### 1️⃣ `roboshop-infra-prod` — Infrastructure as Code (Terraform)

- Cloud: **AWS**
- Infra Components:
  - VPC, Subnets, Internet Gateway
  - Load Balancers (ALB)
  - TLS (via ACM)
  - RDS (MySQL/Postgres)
  - CloudFront CDN
- CI/CD: **Jenkins Pipelines** for provisioning + teardown
- Modular structure with reusable Terraform modules

📌 Repo: [roboshop-infra-prod](https://github.com/Gopi76s/roboshop-infra-prod)

📸 Diagram:  
![Architecture](https://raw.githubusercontent.com/Gopi76s/roboshop-infra-prod/main/infra.jpg)

---

### 2️⃣ RoboShop Application — Microservices Deployment

- Services: `user`, `catalogue`, `cart`, `shipping`, `payment`, `frontend`
- Deployments via:
  - `Shell Scripts` (`roboshop-shell`)
  - `Ansible` roles for config management
  - `Docker` containers
  - `Kubernetes` (via `k8-*` repos, `helm-charts`)
  - App-level provisioning via Terraform modules

🧩 Repos:  
- [gopi-tech](https://github.com/gopi-tech) — initial versions & scripting  
- [gopi-tools](https://github.com/gopi-tools) — refined automation & Helm-based deployments

---

## 🚀 Why This Project Matters

- Combines both **infrastructure** and **application lifecycle**
- Uses **real DevOps workflows** like provisioning, scaling, teardown
- Simulates challenges like **modularity**, **secrets handling**, **CI/CD automation**
- Demonstrates ability to work across **cloud, container, and configuration layers**

---

## 🧰 Tech Stack

| Category               | Tools / Technologies                            |
|------------------------|--------------------------------------------------|
| **IaC**                | Terraform, Shell, Ansible                        |
| **Cloud**              | AWS (EKS, VPC, ALB, RDS, ACM, S3, CloudFront)   |
| **Containers**         | Docker, Kubernetes, Helm                        |
| **CI/CD**              | Jenkins, GitHub Actions, Groovy Pipelines       |
| **Scripting**          | Bash, Shell, Jinja                              |
| **Environments**       | Dev & Prod                                       |

---

## 📫 Contact

I’m currently looking for **on-site roles** where I can bring hands-on automation experience and SRE practices to production teams.

- 💼 Role: **Site Reliability Engineer / DevOps Engineer**
- 📍 Location preference: Bengaluru, Hyderabad, Chennai, Pune
- 📧 Reach me via GitHub [@Gopi1214](https://github.com/Gopi1214)

> _"I built RoboShop to master infrastructure as code and real-world microservices automation — not as a demo, but as a deep-dive."_  
> — Gopi
