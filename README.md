# Windows SOC Detection Lab

## Overview

This project demonstrates a Windows-based Security Operations Center (SOC) Detection Lab using Wazuh SIEM, Sysmon, and Windows Server 2022.

The objective was to collect, monitor, and analyze security events while simulating common attack and administrative activities.

## Architecture

Windows Server 2022

↓

Sysmon

↓

Wazuh Agent

↓

Wazuh Manager

↓

Wazuh Dashboard

## Technologies Used

* Windows Server 2022
* Wazuh SIEM
* Wazuh Agent
* Sysmon
* Windows Event Logs

## Detection Scenarios

### Privileged Logon Monitoring

* Event ID: 4672
* Detection of privileged account logons.

### User Account Creation Detection

* Event ID: 4720
* Detection of newly created user accounts.

### Administrator Group Membership Changes

* Event ID: 4732
* Detection of users added to privileged groups.

### Sysmon Process Monitoring

* Monitoring process creation events using Sysmon.
* Enhanced endpoint visibility and activity tracking.

## Skills Demonstrated

* SIEM Monitoring
* Security Event Analysis
* Windows Event Log Monitoring
* Endpoint Visibility with Sysmon
* Threat Detection
* Blue Team Operations
* SOC Analyst Workflow

## Screenshots

The repository includes screenshots of:

* Wazuh Agent Connectivity
* Sysmon Configuration
* Security Event Detections
* Wazuh Dashboard Visualizations

## Author

Umed Ali

Cybersecurity | SOC Operations | Blue Teaming
