# SOC Home Lab – Security Monitoring & Detection

A Windows-based SOC home lab created to practice security monitoring, log analysis, detection engineering, alert investigation, and incident analysis using Microsoft Sysmon and Windows Event Viewer.

## Objectives

- Set up a controlled SOC monitoring environment
- Collect and analyze Windows security events
- Monitor process creation and authentication events
- Create basic detection rules
- Investigate alerts and identify potential IOCs
- Assign severity based on event context
- Document investigation findings

## Tools Used

- Windows 10
- Microsoft Sysmon
- Windows Event Viewer
- PowerShell
- Command Prompt

## Lab Architecture

Windows Endpoint
→ Sysmon
→ Windows Event Logs
→ Event Viewer
→ Custom Detection Views
→ Alert Investigation
→ IOC & Severity Analysis

## Detection Use Cases

### 1. PowerShell Process Creation

**Source:** Microsoft Sysmon  
**Event ID:** 1 – Process Create

A custom detection was created to identify PowerShell process execution.

A controlled test command was executed:

```powershell
powershell.exe -NoProfile -Command "Write-Output 'SOC LAB TEST'"
## Project Skills Demonstrated

- Windows Security Monitoring
- Sysmon Configuration and Monitoring
- Log Analysis
- Detection Engineering
- PowerShell Monitoring
- Authentication Event Analysis
- IOC Identification
- Alert Triage
- Severity Classification
- Security Investigation Documentation

## Portfolio

This project was completed as part of my SOC Analyst internship practical work and demonstrates hands-on experience with endpoint monitoring, detection creation, event investigation, and security analysis in a controlled lab environment.
