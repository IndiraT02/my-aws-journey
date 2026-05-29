# My AWS Cloud Journey ☁️
### Indira Tiruveedhula | AWS Cloud Practitioner | Terraform Learner

---

## ✅ Project 1 — AWS Cloud Infrastructure (COMPLETED)

### What I Built
A complete AWS infrastructure from scratch including 
networking, compute, storage and monitoring.

### Architecture
Internet
│
[S3 Static Website] ← Portfolio hosted on S3
│
[Internet Gateway]
│
[VPC: 10.0.0.0/16]
├── Public Subnet (10.0.1.0/24) — us-east-1a
│       └── EC2 Web Server (Apache)
└── Private Subnet (10.0.2.0/24) — us-east-1b
└── Reserved for databases/backend
│
[CloudWatch Dashboard]
└── CPU, NetworkIn, NetworkOut monitoring
└── Alarms → SNS Email Alerts

### Services Used
| Service | Purpose |
|---|---|
| Amazon S3 | Static website hosting |
| Amazon VPC | Custom private network |
| Amazon EC2 | Virtual web server (Apache) |
| Amazon CloudWatch | Monitoring and alerting |
| Amazon SNS | Email notifications |
| Security Groups | Firewall rules |
| Internet Gateway | VPC internet access |
| Route Tables | Traffic routing |

### Key Achievements
- Hosted live static website on S3
- Built VPC with public/private subnets from scratch
- Launched EC2 in custom VPC with working web server
- Set up real-time monitoring dashboard with email alerts

---

## 🔄 Project 2 — Terraform AWS Infrastructure (IN PROGRESS)
Infrastructure as Code — provisioning AWS resources using Terraform

---

## ⏳ Project 3 — CI/CD Pipeline (Coming Soon)
M.Tech Final Year Project — BITS Pilani 2026

---

## 🏆 Certifications
- ✅ AWS Certified Cloud Practitioner (March 2026)
- 🔄 Terraform — Currently Learning

## 📫 Connect
- LinkedIn: linkedin.com/in/indira-tiruveedhula-b01000379
- Email: indiratiruveedhula02@gmail.com