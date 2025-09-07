# 👋 Hi, I'm Gopi — Site Reliability Engineer | DevOps Automation Specialist

I design and automate **production-ready infrastructure** using Terraform, Kubernetes, and CI/CD pipelines. My work emphasizes reliability, scalability, and secure automation—optimized for real-world deployment needs.

---

## 💼 Current Role: Site Reliability Engineer (SRE)

As an SRE, I build tools and modules that make infrastructure deployment faster, safer, and repeatable—focused on reliability across development and production environments.

---

## 🔧 Flagship Project: `roboshop-infra-prod`

A complete, production-ready infrastructure repository using **Terraform + Jenkins**, deployed on **AWS** and structured for microservices.

###  Key Features

- Modular provisioning with Terraform:
  - VPC, Subnets, Route Tables
  - Security Groups & VPN
  - RDS Databases
  - App & Web Load Balancers
  - TLS via ACM
  - CDN (CloudFront)
  - Microservices: User, Cart, Catalogue, Shipping, Payment
- CI/CD Pipelines:
  - `Jenkinsfile` – Infrastructure provisioning
  - `Jenkinsfile-destroy` – Clean teardown pipeline

###  Architecture Diagram

![Infrastructure Diagram](https://raw.githubusercontent.com/Gopi76s/roboshop-infra-prod/main/infra.jpg)


###  Infrastructure Metrics

| Metric                    | Value                           |
|---------------------------|----------------------------------|
| Terraform Apply Time      | ~8 minutes                      |
| Terraform Destroy Time    | ~3 minutes                      |
| Modules Used              | 10+ reusable modules            |
| Environments Supported    | Dev, Prod                       |
| CI/CD Toolchain           | Jenkins + Terraform             |
| Security Practices        | ACM for TLS, IAM least privilege |

###  Repo Link:
[roboshop-infra-prod](https://github.com/Gopi76s/roboshop-infra-prod)

---

##  GitHub Organization Journey

###  [gopi-tech](https://github.com/gopi-tech) (2023–2024)
Early-stage automation work focusing on:
- Shell-based infra scripting (`roboshop-shell`, etc.)
- Kubernetes manifests (`k8-*`)
- Terraform modules (`terraform-aws-*`)
- Ansible roles and Docker tooling

###  [gopi-tools](https://github.com/gopi-tools) (2025+)
Refined, modular infrastructure tooling:
- Production-ready modules
- CI/CD scripts
- Secure, resilient infrastructure practices

---

##  Tech Stack

| Area                     | Tools / Technologies                            |
|--------------------------|--------------------------------------------------|
| **IaC**                  | Terraform, Ansible, Shell                        |
| **CI/CD**                | Jenkins, GitHub Actions, Groovy                  |
| **Scripting**            | Bash, Jinja, Shell                              |
| **Cloud Infrastructure** | AWS (VPC, EKS, ALB, ACM, RDS, CDN, IAM)          |
| **Containers & Orchestration** | Docker, Kubernetes, Helm                  |
| **Security & Compliance**| TLS via ACM, Terraform state security, IAM best practices |

---

##  Explore My Work

-  **Infra Project**: [roboshop-infra-prod](https://github.com/Gopi76s/roboshop-infra-prod)  
-  **Foundational Org**: [gopi-tech](https://github.com/gopi-tech)  
-  **Advanced Org**: [gopi-tools](https://github.com/gopi-tools)  
-  **My Profile**: [Gopi1214](https://github.com/Gopi1214)  

---

##  Connect With Me

I'm open to:
- On-site SRE or DevOps roles in **Bengaluru** or nearby regions
- Collaborations focused on infra automation and resiliency
- Team discussions around production-grade deployment practices

> _"Automate strongly. Recover quickly. Build with resilience in mind."_ — My SRE philosophy.
