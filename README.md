# SIEM Business Continuity and Risk Management

A complete business continuity, risk management, and disaster recovery plan for a Security Information and Event Management (SIEM) platform.

## Project Overview

The project analyzes a SIEM platform as a mission-critical cybersecurity system responsible for collecting, analyzing, and correlating security events from across an organization's IT environment.

The plan focuses on maintaining security visibility, reducing downtime, protecting log data, and ensuring fast recovery during disruptions.

## SIEM Functions

The system supports:

- Log collection and aggregation
- Event correlation and analysis
- Real-time threat detection
- Security alerting and escalation
- Incident investigation
- Continuous security monitoring
- Risk and compliance reporting

## Risk Management Framework

The project applies:

**NIST SP 800-30 — Guide for Conducting Risk Assessments**

The framework is used to identify:

- Assets
- Threats
- Vulnerabilities
- Likelihood
- Impact
- Risk scores
- Risk treatment strategies

## Main Risks Identified

The risk register includes:

- DDoS attacks
- Log data tampering
- Unauthorized database access
- Correlation engine misconfiguration
- Network failure
- Insider threats
- Log loss
- Hardware failure
- Credential theft
- Compliance data leakage

## Business Impact Analysis

The SIEM platform achieved a criticality score of:

**4.45 / 5**

This indicates that the system is highly critical and must receive high recovery priority.

## Recovery Objectives

- **Recovery Time Objective (RTO):** 2 hours
- **Recovery Point Objective (RPO):** 15 minutes
- **Work Recovery Time (WRT):** 1 hour
- **Maximum Tolerable Downtime (MTD):** 4 hours

## Backup Strategy

The continuity plan uses a hybrid backup approach:

- Weekly full backups
- Incremental backups every 15 minutes
- Offsite cloud backup storage
- Log, configuration, and correlation-rule backups

## High Availability and Recovery

The architecture includes:

- Primary SIEM server
- Secondary standby server
- Automatic failover
- SIEM clustering
- RAID 10 storage
- Cloud replication
- Warm recovery site
- Manual log monitoring as a temporary workaround

## Architecture

The continuity architecture connects:

- Servers
- Firewalls
- Applications
- Endpoints
- SIEM log collection and correlation
- Backup systems
- Cloud storage
- Primary and secondary servers
- Warm recovery infrastructure

## Project File

Open `SIEM_Business_Continuity_Risk_Management.pdf` to view the complete report.

## Team

- Eiad Hamdy
- Loay Waleed
- Omar Samer
- Marwan Ahmed
- Ali Mohab
