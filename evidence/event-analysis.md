# SOC Alert Investigation – Event Analysis

## Overview

This document records the analysis of two security events generated
during a controlled Windows SOC lab.

The events were intentionally generated for educational testing and
do not represent a real security incident.

---

# Investigation 1 – PowerShell Process Creation

## Detection

- Log Source: Microsoft Sysmon
- Event ID: 1
- Event Type: Process Create
- Detection: PowerShell process execution
- Severity: Low / Informational

## Test Activity

The following harmless command was executed:

```powershell
powershell.exe -NoProfile -Command "Write-Output 'SOC LAB TEST'"
