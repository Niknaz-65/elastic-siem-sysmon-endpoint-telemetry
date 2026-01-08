# Elastic SIEM + Sysmon, Endpoint Telemetry Pipeline

## Objective
Build and validate an endpoint telemetry pipeline for SOC visibility using Elastic SIEM and Sysmon.

## Environment
- Elastic SIEM (Elastic Cloud)
- Elastic Agent with Fleet
- Windows endpoint
- Sysmon v15+
- KQL
- Kibana

## Data Collected
- Process creation events
- Network connection events
- PowerShell execution events
- Windows security telemetry

## Architecture
Windows Endpoint → Sysmon → Elastic Agent (Fleet) → Elastic SIEM → Kibana

## Validation Evidence

![Kibana Discover, Sysmon Endpoint Telemetry](screenshots/kibana-discover-sysmon.png)

## SOC Relevance
This project demonstrates endpoint telemetry ingestion, SIEM validation, and investigation-ready visibility aligned with SOC analyst workflows and MITRE ATT&CK techniques.




