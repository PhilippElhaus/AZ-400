# AZ-400 Exam Prep – Microsoft Certified: DevOps Engineer Expert

This repository contains categorized PDF question sets for the AZ-400 certification. Content is aligned with the official Microsoft Learn skill outline (April 2025).

## Overview

The AZ-400 exam validates skills related to:
- Designing and implementing processes and communications
- Designing and implementing a source control strategy
- Designing and implementing build and release pipelines
- Developing a security and compliance plan
- Implementing an instrumentation strategy

## Skills Outline Coverage

### 1. Pocesses and communications (10–15%)

#### 1.1 Traceability and flow of work
- ✅ Design and implement GitHub Flow
- ✅ Design and implement feedback cycles (notifications, GitHub issues)
- ✅ Integrate GitHub Projects, Azure Boards, repositories
- ✅ Implement source, bug, and quality traceability

#### 1.2 Metrics and queries for DevOps
- ✅ Dashboards: cycle time, time to recovery, lead time
- ✅ Metrics/queries for: planning, development, testing, security, delivery, operations

#### 1.3 Configure collaboration and communication
- ✅ Document projects with wikis and diagrams (Markdown, Mermaid)
- ✅ Configure release documentation (release notes, API docs)
- ✅ Automate documentation from Git history
- ✅ Integrate using webhooks, GitHub/Azure Boards, Teams

### 2. Source control strategy (10–15%)

#### 2.1 Branching and workflows
- ✅ Branch strategies: trunk-based, feature, release
- ✅ Pull request workflows with policies
- ✅ Branch protections and merge restrictions

#### 2.2 Repository configuration and maintenance
- ✅ Manage large files (Git LFS, git-fat)
- ✅ Optimize scaling (Scalar, cross-repo)
- ✅ Configure permissions, tags
- ✅ Recover/remove data with Git commands

#### 2.3 Package management
- ✅ Tools: GitHub Packages, Azure Artifacts
- ✅ Configure feeds/views for packages
- ✅ Versioning strategies: SemVer, CalVer
- ✅ Version pipeline artifacts

### 3. Build and release pipelines (50–55%)

#### 3.1 Package management and testing strategy
- ✅ Quality/release gates (security, governance)
- ✅ Testing strategy: unit, integration, load
- ✅ Tests in pipelines: agents, result integration
- ✅ Code coverage analysis

#### 3.2 Design and implement pipelines
- ✅ Automation tools: GitHub Actions, Azure Pipelines
- ✅ Runner/agent infra: cost, licenses, connectivity
- ✅ Integration of GitHub repos with Azure Pipelines
- ✅ Pipeline triggers, YAML usage, job execution

#### 3.3 Advanced pipeline design
- ✅ Hybrid pipelines, self-hosted agents, VM templates
- ✅ Reusable elements: YAML templates, task/variable groups
- ✅ Checks and approvals with YAML environments

#### 3.4 Deployment strategy and execution
- ✅ Blue-green, canary, ring, progressive exposure, A/B
- ✅ Ordered dependency deployments
- ✅ Minimize downtime: VIP swap, rolling, slots
- ✅ Hotfix and resiliency planning

#### 3.5 Implement deployment solutions
- ✅ Feature flags with Azure App Configuration
- ✅ Deploy containers, binaries, scripts
- ✅ Database task deployments
- ✅ Configuration management tools/strategies

#### 3.6 Infrastructure as Code (IaC)
- ✅ Define IaC strategy: source control, automation
- ✅ Implement desired state: Bicep, ARM, DSC
- ✅ Azure Deployment Environments (self-deployment)

#### 3.7 Maintain and optimize pipelines
- ✅ Monitor pipeline health (failures, duration)
- ✅ Optimize: cost, time, reliability, performance
- ✅ Artifact retention strategy
- ✅ Migrate classic to YAML

### 4. Security and compliance (10–15%)

#### 4.1 Authentication and authorization
- ✅ Choose: Service Principals, Managed Identity
- ✅ GitHub auth: Apps, tokens
- ❌ Azure DevOps service connections, tokens
- ❌ Permissions/roles in GitHub

#### 4.2 Permissions and access
- ❌ Azure DevOps permissions, security groups
- ❌ Access levels: stakeholders, collaborators
- ❌ Project/team config in Azure DevOps

#### 4.3 Secret and sensitive data management
- ❌ Azure Key Vault secrets/keys/certs
- ❌ Secrets in GitHub Actions/Azure Pipelines
- ❌ Secure files during deployment
- ❌ Prevent sensitive data leakage in pipelines

#### 4.4 Security and compliance scanning
- ❌ Dependency/code/secret/license scanning
- ❌ Microsoft Defender for DevOps Security
- ❌ GitHub Advanced Security
- ❌ CodeQL, container scanning
- ❌ Dependabot for OSS scanning

### 5. Instrumentation (5–10%)

#### 5.1 Monitoring setup
- ❌ Configure Azure Monitor, Log Analytics
- ❌ Telemetry with App Insights, VM/Container/Storage/Network Insights

#### 5.2 Alerting and metrics
- ❌ GitHub monitoring insights/charts
- ❌ Alerts in GitHub Actions and Azure Pipelines

#### 5.3 Metrics and telemetry analysis
- ❌ Inspect: CPU, memory, disk, network
- ❌ Analyze app usage/performance metrics
- ❌ Distributed tracing with App Insights
- ❌ Kusto Query Language (KQL) basics

## 📚 Resources

- [AZ-400 Certification Overview](https://learn.microsoft.com/en-us/credentials/certifications/devops-engineer/)
- [Microsoft Learn: AZ-400 Training Paths](https://learn.microsoft.com/en-us/training/paths/devops-engineer/)
- [Practice Assessment](https://learn.microsoft.com/en-us/credentials/certifications/devops-engineer/practice/assessment)
