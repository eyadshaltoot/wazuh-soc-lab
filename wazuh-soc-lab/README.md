# Wazuh SOC Lab

## Overview

This project demonstrates a Security Operations Center (SOC) lab built using Wazuh SIEM and a Windows endpoint.

## Lab Architecture

* Wazuh Server (Ubuntu)
* Windows 10 Endpoint (with Sysmon)
* Kali Linux (Attacker)

## Tools Used

* Wazuh SIEM
* Sysmon
* VMware

## Attack Scenarios

* PowerShell execution
* File drop simulation
* Persistence via registry
* Command & Control behavior

## Detection

* Detected suspicious PowerShell activity
* Identified file creation in system directories
* Mapped alerts to MITRE ATT&CK (T1105, T1574)

## Incident Analysis

Multiple suspicious activities were correlated into a multi-stage attack involving execution, file drop, and persistence.

## Skills Demonstrated

* SIEM deployment
* Log analysis
* Threat detection
* Incident analysis
