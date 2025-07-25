# DevOps Infrastructure Monitoring & Automation Project

## 🚀 Overview
This project automates the setup of infrastructure monitoring using **Ansible**, **Docker**, **Prometheus**, **Grafana**, and **Node Exporter** on a local/WSL environment.

---

---

## 🧰 Tools & Versions

| Tool         | Version       |
|--------------|---------------|
| Git          | x.x.x         |
| VS Code      | x.x.x         |
| Docker       | x.x.x         |
| Ansible      | x.x.x         |
| Prometheus   | x.x.x         |
| Grafana      | x.x.x         |
| Node Exporter| x.x.x         |
| OS (WSL)     | Ubuntu 20.04+ |

---

### Module 1: Git & Project Setup
- ✅ Created `infra-monitoring-project` repo
- ✅ Pushed initial folder structure and README

### Module 2: Prometheus Setup
- ✅ Installed Docker & Docker Compose
- ✅ Ran Node Exporter and Prometheus containers
- ✅ Verified metrics scraping in Prometheus UI

### Module 3: Grafana Dashboards
- ✅ Ran Grafana in Docker
- ✅ Connected to Prometheus
- ✅ Customized dashboards with CPU, Memory, and Disk panels

### Module 4: Ansible Automation
- ✅ Wrote Ansible playbooks for setup and monitoring deployment
- ✅ Used inventory.ini for localhost targeting
- ✅ Ensured idempotent execution and success

### Module 5: Final Review
- ✅ Documented architecture, tool versions, configurations
- ✅ Pushed everything to GitHub

---
---

## 📸 Screenshots

- Prometheus UI
- Grafana Dashboard
- Ansible Playbook Output
- Folder Structure
- Architecture Diagram

---

## 📁 Configuration Files

- [`automation/inventory.ini`](automation/inventory.ini)
- [`automation/setup.yml`](automation/setup.yml)
- [`automation/deploy-monitoring.yml`](automation/deploy-monitoring.yml)
- [`monitoring/docker-compose.yml`](monitoring/docker-compose.yml)
- [`monitoring/prometheus/prometheus.yml`](monitoring/prometheus/prometheus.yml)

---

## 💡 Learnings

- Automating infrastructure using Ansible
- Monitoring metrics using Prometheus & Node Exporter
- Visualizing data with Grafana dashboards
- Container orchestration via Docker Compose
- Managing code versioning via Git & GitHub

---

## 🔗 Live / Local Access

- Prometheus: http://localhost:9090
- Grafana: http://localhost:3000

---

## 📌 Final Submission
- ✅ GitHub Repo: https://areebahassan01/infra-monitoring-project
