
# 🛡️ PTaaS Security Demo

[![](https://img.shields.io/badge/status-Demo--Only-informational?style=flat-square)](#)
[![](https://img.shields.io/badge/project-type-Modular_PTaaS-blueviolet?style=flat-square)](#)
[![](https://img.shields.io/badge/security-Automated-green?style=flat-square)](#)
[![](https://img.shields.io/badge/built_with-Terraform-623CE4?logo=terraform&logoColor=white&style=flat-square)](#)
[![](https://img.shields.io/badge/built_with-Kubernetes-326CE5?logo=kubernetes&logoColor=white&style=flat-square)](#)
[![](https://img.shields.io/badge/Secrets-HashiCorp_Vault-000000?logo=vault&logoColor=white&style=flat-square)](#)
[![](https://img.shields.io/badge/IaC-Ansible-EE0000?logo=ansible&logoColor=white&style=flat-square)](#)
[![](https://img.shields.io/badge/CI/CD-GitHub_Actions-2088FF?logo=githubactions&logoColor=white&style=flat-square)](#)
[![](https://img.shields.io/badge/Monitoring-Prometheus-orange?logo=prometheus&logoColor=white&style=flat-square)](#)
[![](https://img.shields.io/badge/Dashboards-Grafana-F46800?logo=grafana&logoColor=white&style=flat-square)](#)
[![](https://img.shields.io/badge/Logging-ELK_Stack-005571?style=flat-square)](#)
[![](https://img.shields.io/badge/Scanner-Trivy-lightgrey?style=flat-square)](#)
[![](https://img.shields.io/badge/DAST-OWASP_ZAP-034638?style=flat-square)](#)
[![](https://img.shields.io/badge/Web_Scanner-Nikto-8A2BE2?style=flat-square)](#)
[![](https://img.shields.io/badge/Network_Scanner-OpenVAS-006400?style=flat-square)](#)
[![](https://img.shields.io/badge/Visit_Portfolio-mystshara.github.io-9cf?style=flat-square)](https://mystshara.github.io)

---

> ⚠️ This is a **trimmed, public-facing version** of a larger modular PTaaS platform currently under private development.  
> 📫 For more information, access, or collaboration opportunities, please reach out via [my portfolio](https://mystshara.github.io).

---

## 🧠 Overview

This repository provides an overview of a modular **Penetration Testing as a Service (PTaaS)** automation stack.  
Built for scalable vulnerability lifecycle management, the platform integrates DevSecOps workflows with secure, reproducible pipelines.

It features IaC-driven provisioning, secrets management, dynamic container orchestration, and automated task scheduling.

---

## 🧩 Architecture Highlights

### 🔧 Infrastructure as Code
- **Terraform** handles cloud resource provisioning.
- **Ansible** automates configuration across environments.

### 🔐 Secrets Management
- **HashiCorp Vault** secures tokens, API keys, and sensitive credentials.
- Designed around a zero-trust approach.

### 📦 Container Orchestration
- **Kubernetes** is used to manage containerized security tools and workers.

### 🔁 Task Automation
- **Celery + Cron** execute scanning cycles and periodic tasks.
- Seamless integration into CI/CD flows.

### 🧪 Security Toolchain
- **Trivy** — container & image scanning
- **OWASP ZAP** — DAST (Dynamic App Security Testing)
- **Nikto** — web server vulnerability scanning
- **OpenVAS** — network-based vulnerability scanning

### 🚀 CI/CD & Observability
- **GitHub Actions** — automated secure builds, deployments, and triggers
- **Prometheus & Grafana** — real-time system monitoring
- **ELK Stack** — log aggregation and event correlation

---

## 🗂️ Repository Contents

This public demo includes only **non-sensitive**, educational examples:

| Section             | Status       |
|---------------------|--------------|
| `main.tf`           | ✅ Minimal example |
| `docker-compose.yml` | ✅ Demo version |
| `ansible/roles/`    | ✅ Template included |
| Architecture Diagram| ⏳ Coming soon |
| Scripts & Scanners  | ⏳ Coming soon |
| Secrets/Private Keys| ❌ Not included |

---

## 📌 Project Purpose

This repository serves as a **safe reference architecture** for:
- Those learning secure infrastructure automation
- Demonstrating DevSecOps capabilities to recruiters or collaborators
- Public portfolio visibility without exposing private code

---

## 👩‍💻 About the Developer

**Rebecca Turner**  
DevSecOps & Security Automation Engineer  
Focused on infrastructure security, CI/CD pipelines, containerization, and scalable PTaaS platforms.

🔗 [Portfolio](https://mystshara.github.io)  
💼 [LinkedIn](https://www.linkedin.com/in/rebecca-turner-81377598)

---

## 📬 Want to Connect?

If you'd like to collaborate, gain access to the full repo, or just ask questions — I’d love to hear from you!

→ [Contact me here](https://mystshara.github.io#contact)

---

> 🧪 *This project is in active development. Stay tuned for updates!*
