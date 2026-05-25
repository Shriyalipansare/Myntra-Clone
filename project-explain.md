
# 🛠️ Myntra Clone – CI/CD DevOps Pipeline

---

## 🔧 Tech Stack

- **NodeJS** – Application code
- **Jenkins** – Continuous Integration
- **SonarQube** – Code quality and vulnerability scan
- **Docker** – Containerization
- **DockerHub** – Container image registry
- **ArgoCD** – Continuous Delivery with GitOps
- **EKS (Elastic Kubernetes Service)** – Kubernetes hosting
- **Prometheus & Grafana** – Monitoring and visualization

---

## 📌 Project Overview

**“So this was a complete CI/CD project for a Myntra clone application.
I started with the NodeJS code hosted on GitHub. Jenkins handles the pipeline —
it pulls the code, runs a SonarQube scan to check for bugs and vulnerabilities,
and waits for the quality gate to pass.”**

---

## ⚙️ CI/CD Workflow

**“Once that’s done, Jenkins builds a Docker image and pushes it to DockerHub.
Then instead of deploying directly, I follow a GitOps model —
Jenkins updates the Kubernetes deployment file in GitHub with the new image tag.”**

---

## 🚀 GitOps Deployment with ArgoCD

**“ArgoCD watches that Git repo. As soon as it detects the change in the manifest,
it syncs and deploys the updated app to the Kubernetes cluster running on AWS EKS.
This keeps everything version-controlled and automatic.”**

---

## 🔒 Security Measures

**“For security, I enabled HTTPS on ArgoCD using Ingress and cert-manager, and
integrated GitHub SSO to avoid using static admin credentials. I also used Trivy to scan Docker images.”**

---

## 📊 Monitoring & Observability

**“For monitoring, I set up Prometheus to collect metrics from the EKS cluster and
used Grafana to visualize everything like CPU, memory, and pod health.”**

---

## ✅ Summary

**“So overall, the project showcases how I can build and manage a secure, automated, and
observable CI/CD pipeline using modern DevOps tools and best practices.”**

---