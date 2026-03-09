# Cloud Infrastructure Automation & Monitoring Stack

This project demonstrates a fully automated deployment of a professional monitoring stack using **Ansible**, **Docker Compose**, and **Nginx** as a Reverse Proxy.

## 🚀 Architecture Overview
The system is designed to provide real-time metrics and logs collection for cloud instances (AWS EC2).

- **Nginx**: Acts as a single gateway (Port 80) routing traffic to various services.
- **Grafana**: Data visualization and dashboards.
- **Prometheus**: Time-series database for system metrics.
- **Node Exporter**: Collects hardware and OS metrics.
- **Loki & Promtail**: Centralized logging system.

## 🛠️ Tech Stack
- **Infrastructure as Code:** Ansible
- **Containerization:** Docker & Docker Compose V2
- **Monitoring:** Prometheus & Grafana
- **Logging:** Loki & Promtail
- **Web Server:** Nginx

## 📸 Dashboard Preview
![Monitoring Dashboard](https://github.com/gaby322/infra-automation/blob/master/path-to-your-screenshot.png) 
*(Note: Upload your screenshot to GitHub and update this link)*

## ⚙️ How to Deploy
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/gaby322/infra-automation.git](https://github.com/gaby322/infra-automation.git)
   cd infra-automation
