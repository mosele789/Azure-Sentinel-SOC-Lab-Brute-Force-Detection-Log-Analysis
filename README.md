# Azure Sentinel SOC Lab – Brute Force Detection & Log Analysis

## Overview

This project demonstrates the deployment and configuration of a cloud-based Security Operations Center (SOC) lab using Microsoft Azure and Microsoft Sentinel. The lab was designed to simulate real-world security monitoring by ingesting Windows Security Event logs, analyzing authentication activity using Kusto Query Language (KQL), and creating custom detection rules for brute-force login attempts.

The project focuses on foundational SOC analyst skills including telemetry ingestion, log analysis, threat detection, incident correlation, and alert engineering.

## Objectives

- Deploy a Windows virtual machine in Microsoft Azure
- Configure Microsoft Sentinel SIEM integration
- Ingest Windows Security Event logs into Log Analytics Workspace
- Analyze authentication telemetry using KQL queries
- Detect failed login attempts and brute-force behavior
- Create custom analytics and detection rules
- Map alerts to MITRE ATT&CK techniques
- Gain hands-on experience with cloud-based SOC operations

## Architecture

Internet
   ↓
Azure Windows Virtual Machine
   ↓
Azure Monitor Agent (AMA)
   ↓
Log Analytics Workspace
   ↓
Microsoft Sentinel SIEM
   ↓
KQL Queries & Detection Rules
   ↓
Security Alerts & Incident Correlation

# Phase 1 — Azure Environment Setup

## Step 1 — Created Azure Resource Group

A dedicated resource group was created to organize all cloud resources associated with the SOC lab environment.

### Purpose
- Centralized management of resources
- Simplified deployment and cleanup
- Improved resource visibility

### Resources Included
- Windows Virtual Machine
- Log Analytics Workspace
- Microsoft Sentinel
- Networking Components

![Azure Resource Group](images/resource-group.png)
![Azure Resource Group](images/resource-group.png)

