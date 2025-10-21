🛡️ Defense-in-Depth on Azure
📘 Overview

This project demonstrates the implementation of a Defense-in-Depth architecture on Microsoft Azure, leveraging multiple security layers to protect cloud workloads and network infrastructure. The deployment includes key Azure services for identity, network, and data protection.

🧩 Architecture Components
Layer	Azure Service	Purpose
Network Security	Azure Firewall	Filters and controls inbound/outbound traffic between subnets
Monitoring & Logging	Log Analytics Workspace	Centralized log collection and query-based monitoring
Data Collection Rules (DCR)	Azure Monitor	Defines which telemetry data is collected and where it’s sent
Managed Identity	System-Assigned Identity	Provides secure, passwordless authentication for the web server
Subnets	Virtual Network (VNet)	Logical network segmentation for isolating workloads

⚙️ Deployment Details

Deployment Type: ARM Template / Bicep Deployment

Resource Group: 923e3945f3-implement-defense-in-depth-on-azure

Subscription: PS-Real Hands-On-Lab

Status: ✅ Deployment completed successfully

Key Deployment Successes

Azure Firewall and Management Subnets created

Log Analytics workspace deployed

Data Collection Endpoint configured

Managed Identity successfully enabled

🔍 Monitoring & Insights

Logs and telemetry data are collected via Azure Monitor and Log Analytics, enabling:

Network traffic visibility

Security event analysis

Compliance and alerting dashboards

🏗️ Next Steps

Integrate Microsoft Defender for Cloud for continuous security posture management

Configure Network Security Groups (NSGs) and Application Rules

Automate policy enforcement via Azure Policy

