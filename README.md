# Agentic AI for Cloud Ops on AWS

Build AI agents that operate your AWS infrastructure autonomously.

This isn't "ask ChatGPT about AWS." This is about AI agents that reason through multi-step problems, use tools, interact with your AWS environment, and take action on your behalf.

## What You'll Build

- **AWS Operator Agent** — execute multi-step AWS operations in natural language
- **Incident Investigator Agent** — autonomously debug production infrastructure issues
- **IaC Agent** — generate, review, and explain Terraform/CloudFormation
- **Cost Investigator Agent** — find billing anomalies and wasted resources
- **Deployment Review Agent** — pre-deployment risk assessment

## Prerequisites

- AWS account with CLI configured
- Working knowledge of AWS core services (VPC, EC2, IAM, CloudWatch)
- Basic IaC experience (Terraform or CloudFormation)

## Getting Started

Each section has its own folder with a CloudFormation template and a demo script.

```bash
cd section-1-intro
./run-demo.sh deploy    # Deploy the demo infrastructure
./run-demo.sh break     # Simulate a misconfiguration
./run-demo.sh destroy   # Clean up when done
```

## Course

By [CloudYeti](https://www.youtube.com/@cloudyeti)
