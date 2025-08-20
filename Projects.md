🚀 Project  - **SaaS Product Infrastructure (SAP + ML Integration on GCP & AWS)**

I worked on setting up multi-cloud infrastructure to support a SaaS product that connected SAP compliance data with ML-based classification models. The project required building scalable, secure, and automated infra across GCP and AWS while enabling cross-team collaboration.

🔧 What I Did

Designed VPC peering and secure network architecture for SAP systems in GCP.

Automated infra setup with Terraform modules for GCP + AWS, making environments reproducible.

Implemented CI/CD pipelines in GitHub Actions, using submodules for each microservice/project.

Built deployment automation for ML models and SAP connectors.

Added observability using Prometheus, Grafana, and logging integrations for proactive monitoring.

Created shared playbooks and runbooks so ML and SAP teams could self-serve deployments without depending on Infra/DevOps.

Collaborated via Azure Boards for sprint tracking, backlog management, and cross-team alignment.

Wrote documentation for onboarding, CI/CD flows, and infra usage, which reduced ramp-up time for new engineers.

⚡ Challenges & How I Solved Them

Challenge: SAP systems had strict compliance and network isolation.
✅ Solution: Implemented VPC Service Controls + secure peering between SAP and ML workloads.

Challenge: Different teams (ML vs SAP) had varied deployment needs.
✅ Solution: Built modular Terraform + GitHub CI/CD submodules and self-service playbooks, so teams deployed independently.

Challenge: Monitoring ML workloads and SAP jobs was fragmented.
✅ Solution: Unified observability dashboards across systems with Grafana and Cloud Monitoring.

🌟 Key Outcomes

Reduced deployment time from hours to minutes with automation.

Enabled cross-team collaboration between SAP, ML, and DevOps.

Improved reliability with observability-first approach.

Delivered a scalable SaaS product infra with automated deployments in both GCP and AWS.
