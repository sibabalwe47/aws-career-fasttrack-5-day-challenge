# 🛠️ AWS Project: Scalable Infrastructure with Terraform & CI/CD

This is the AWS infrastructure project I built as part of the **AWS Career FastTrack 5-Day Challenge** — a hands-on program designed to help aspiring cloud engineers build real-world skills, visibility, and career leverage.

Over 5 days, I built and deployed a complete AWS environment using **Terraform**, **GitHub Actions**, and best practices in infrastructure design — and I’m proud to showcase the results here.

---

## 🚀 Project Overview

This project simulates a production-ready environment that includes:

- A custom **VPC** setup with public and private subnets
- EC2 or ECS-based application hosting
- IAM roles and policies for secure access control
- An S3 bucket for static asset storage or logs
- A **CI/CD pipeline** using GitHub Actions for automated deployments

---

## 💡 Why I Built This

Most cloud learners stop at theory or certifications. I wanted to:

- Prove I could build a real AWS system from scratch
- Gain hands-on experience with Infrastructure as Code
- Learn how to use CI/CD to automate deployments
- Create a **public, reviewable GitHub repo** to show to recruiters and hiring managers

This project is now a key part of my cloud portfolio — and I’ll continue building on it to grow my skills.

---

## 📂 Tech Stack

| Layer                  | Tools Used              |
| ---------------------- | ----------------------- |
| Infrastructure as Code | Terraform               |
| Cloud Provider         | AWS (Free Tier)         |
| CI/CD                  | GitHub Actions          |
| Architecture Diagram   | Excalidraw / Lucidchart |
| Code Editor            | VS Code                 |
| Version Control        | Git + GitHub            |

---

## 📸 Architecture Diagram

_Insert your architecture diagram here (Eraser / Lucidchart / Excalidraw export)_

---

## 🔄 How It Works

1. Infrastructure is defined in Terraform using modules and variables.
2. On each GitHub push, a GitHub Actions workflow triggers:
   - `terraform plan`
   - `terraform apply` (optional manual approval)
3. AWS services are provisioned and application deployed (EC2/ECS).
4. Logs and metrics are available in AWS CloudWatch (optional).
5. Output: A working environment, versioned in Git, reproducible anytime.

---

## 📈 What I Learned

- How to structure and modularize Terraform code
- How to use GitHub Actions for cloud deployments
- How to plan and justify AWS architecture decisions
- How to turn work into **career visibility** via GitHub and LinkedIn
- The power of executing consistently using a system

---

## 🧭 What’s Next

- Improve monitoring with CloudWatch or OpenTelemetry
- Add RDS or DynamoDB for backend storage
- Explore serverless architecture patterns
- Repeat the challenge structure to build more projects

---

## 🧠 About the Challenge

This project was built during the [AWS Career FastTrack Challenge](#), led by Siba N.. It’s a 5-day system focused on helping aspiring engineers:

- Learn AWS through action
- Build real projects with support
- Share their work for visibility
- Promote themselves strategically
- Track and grow long after the challenge ends

---

## 📬 Let’s Connect

If you're building in the cloud, let’s connect on LinkedIn:  
[Insert your LinkedIn profile URL here]

Feel free to fork this repo or reach out if you have questions!
