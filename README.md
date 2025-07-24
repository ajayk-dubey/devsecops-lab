\# DevSecOps Lab 🚀



This project is a production-grade DevSecOps Lab demonstrating secure CI/CD pipelines for both application and infrastructure deployment. It integrates modern tools across security, automation, and monitoring.



\## 🔐 Security Tools Integrated



\- \*\*Code Scanning\*\*: Semgrep, SonarQube, Gitleaks

\- \*\*Dependency Scanning\*\*: Trivy, OWASP Dependency-Check

\- \*\*Container Scanning\*\*: Dockle, Trivy, Syft

\- \*\*IaC Scanning\*\*: Checkov, TFLint, KubeLinter, Conftest, kube-bench

\- \*\*Vulnerability Management\*\*: DefectDojo



\## 📦 Project Structure

ci-cd/

├── app-pipeline/

│ ├── Jenkinsfile-build-app

│ ├── Jenkinsfile-scan-app

│ └── Jenkinsfile-deploy-app

├── infra-pipeline/

│ ├── Jenkinsfile-build-infra

│ ├── Jenkinsfile-scan-infra

│ └── Jenkinsfile-deploy-infra

envs/

├── dev/ # Region \& environment-specific tfvars

├── test/

├── stage/

└── prod/

modules/

├── global/ # Global networking / IAM modules

└── regional/ # Regional VPC, Subnet, NAT, etc.



assets/ # Diagrams and visual documentation



\## 🌐 Deployment



A static preview of this lab is hosted at: `https://devsecops.netlify.app` \*(update this after Netlify)\*



\## 🧑‍💻 Author



\*\*Ajayd — DevOps Engineer\*\*  

> Sharing modern DevSecOps practices.

---



