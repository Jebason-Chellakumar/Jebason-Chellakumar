# Hi, I'm Jebason Chellakumar 👋

**Cloud Solutions Architect** · AWS · Data Engineering · GenAI & Multi-Agent Systems · DevOps · Cloud Security
📍 Chennai, India · 🏅 AWS Certified Solutions Architect – Associate

I design and run production platforms on AWS. My recent work: lakehouses that bring hundreds of databases into one analytics platform, serverless event-driven backends, CI/CD with security scanning built in, and LLM agents that automate real business workflows.

---

### 🚀 Featured projects

| Project | What it is | Stack |
|---|---|---|
| **[aws-medallion-lakehouse](https://github.com/Jebason-Chellakumar/aws-medallion-lakehouse)** | Multi-tenant CDC lakehouse: replicates many source databases with DMS and merges every change into Bronze/Silver/Gold Iceberg tables. Handles deletes, replays, schema drift and Glue concurrency limits, and runs locally on DuckDB with 42 tests | DMS · S3 · Glue (PySpark) · Apache Iceberg · Athena · Step Functions · CloudFormation |
| **[finops-agent](https://github.com/Jebason-Chellakumar/finops-agent)** | Multi-agent FinOps assistant: an orchestrator sends specialist agents to analyse AWS spend in parallel, finding anomalies, idle non-prod resources and untagged spend. Every number comes from a tested analysis engine | Python · Claude API · multi-agent tool use · AWS Cost Explorer |
| **[bedrock-rag-translator](https://github.com/Jebason-Chellakumar/bedrock-rag-translator)** | Retrieval-augmented translation into many languages that stays consistent with approved past translations and the glossary. Placeholders are masked so they never break, every segment gets automatic QA with self-correction, and real problems go to a human review queue. Runs as a CLI or an S3-triggered Lambda | Amazon Bedrock (Claude, Titan embeddings) · FAISS · Lambda · SAM |

### 🏗️ What I've built at work

- **Enterprise data platform.** I designed and built a DMS → S3 → Glue → Apache Iceberg → Athena medallion lakehouse end to end and **migrated 600+ source databases** into it (RDS MySQL, MongoDB/DocumentDB, DynamoDB). The work covered CDC, deduplication, schema evolution, tenant-aware partitioning and SQLMesh models.
- **Multi-agent AI.** I built an agent system that automates CRM request intake with validation and approval checks, and a Claude-powered multi-agent dashboard for cloud cost monitoring.
- **GenAI / RAG.** I built a RAG translation assistant for multilingual content and an in-app image-generation feature, using Amazon Bedrock, LangChain and FAISS.
- **CI/CD & security ownership.** I own CI/CD and security across a multi-account AWS Organization (Control Tower, IAM Identity Center, SCPs), covering dev, QA, UAT and production in four regions. Releases move branch by branch through CodePipeline, CodeBuild and CodeDeploy, gated by gitleaks secret scanning and SonarQube quality checks, with governance through AWS Config, CloudTrail and CloudWatch.
- **Serverless & DevOps.** I built Lambda / API Gateway / Step Functions workflows, and pipelines with GitHub Actions, SAM, Serverless Framework and Docker/ECR for Python, Node.js, TypeScript and React Native apps.
- **Reliability.** I traced an RDS Proxy connection spike (20 → 278 connections) to EventBridge schedules firing at the same time. I also run disaster-recovery drills for RDS when an Availability Zone fails, and I've resolved RDS saturation and AZ capacity incidents.
- **Security automation.** I automated IAM access-key rotation with no downtime (Lambda, Secrets Manager), set up GuardDuty alerts graded by severity (EventBridge, SNS), and run Scout Suite security scans across all accounts on demand. I also run API DAST with Wapiti and Nikto, patch EC2 with SSM Patch Manager, and enforce CDK permission boundaries, on top of AppScan, MobSF, Trivy and WAF.
- **FinOps.** I cut the EC2 fleet by 40% in six months by moving workloads to serverless, resized the Savings Plan from 25 to 10 instances, and set budgets per organizational unit.
- **Mentoring.** I designed project tracks for cloud and AI interns: RAG chatbots, cost intelligence and agentic AI.

### 🛠️ Tech stack

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-1E88E5?style=flat)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

- **AWS:** Organizations · Control Tower · IAM Identity Center · EC2 · ECS · ECR · Lambda · API Gateway · Step Functions · S3 · RDS · DynamoDB · DocumentDB · VPC · IAM · CloudFormation · SAM · CloudWatch · Glue · Athena · DMS · Redshift · Bedrock · WAF · GuardDuty · Config · CloudTrail · EventBridge · SSM Patch Manager
- **Data:** Glue/PySpark · Apache Iceberg · SQLMesh · CDC · medallion architecture · Parquet
- **AI:** Amazon Bedrock · Claude · LangChain · RAG · FAISS · multi-agent systems
- **DevSecOps:** CodePipeline · CodeBuild · CodeDeploy · GitHub Actions · gitleaks · SonarQube · Trivy
- **Security:** IAM · SCPs · WAF · GuardDuty · CloudTrail · Secrets Manager · Scout Suite · HCL AppScan · MobSF · Trivy · Wapiti · Nikto

### 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jebason-chellakumar)
[![Email](https://img.shields.io/badge/jebasonchellakumar%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:jebasonchellakumar@gmail.com)
