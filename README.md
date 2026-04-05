#  Hybrid Production Incident Response – AWS + Linux

##  Overview

This project simulates a real-world production incident in a cloud-hosted Linux environment, focusing on high CPU service degradation and full incident response.

The goal was to replicate how a Service Operations Analyst investigates, diagnoses, and resolves system-level issues in a live environment.

---

##  Key Highlights

- Simulated a **SEV-1 production incident** on AWS EC2
- Diagnosed high CPU utilization using Linux tools (`top`, `ps`)
- Identified a **runaway process** impacting system performance
- Restored application availability by resolving resource contention
- Validated system recovery using service and network checks
- Implemented a **Python-based health check script** for monitoring

---

##  Environment

- AWS EC2 (Amazon Linux 2023)
- Nginx web server
- SSH remote administration
- Python automation

---

##  Incident Summary

Users reported application slowness.

Investigation revealed excessive CPU utilization caused by a rogue process, which degraded nginx performance.

The issue was isolated, resolved, and validated using standard incident response methodology.

---

##  Incident Lifecycle

Alert → Investigation → Isolation → Root Cause → Resolution → Validation

---

##  Tools & Commands Used

- `top` – real-time CPU monitoring  
- `ps aux` – process analysis  
- `systemctl` – service management  
- `journalctl` – log analysis  
- `ss` – port validation  
- `curl` – application testing  

---

## 🐍 Automation

A Python script was developed to simulate service monitoring by checking nginx health and detecting failures.

---

##  Skills Demonstrated

- Linux system troubleshooting  
- AWS cloud infrastructure  
- Incident response methodology  
- Root cause analysis (RCA)  
- Service recovery and validation  
- Automation mindset  

---


## 📁 Project Breakdown

For full step-by-step execution, commands, and screenshots:

👉 See the detailed project documentation inside this repository.

---

##  Why This Matters

This project reflects real-world operational scenarios and demonstrates the ability to:

- Troubleshoot under pressure  
- Work across cloud and Linux environments  
- Communicate and resolve incidents effectively  

---

##  Outcome

Successfully simulated, diagnosed, and resolved a production-style incident while documenting the full lifecycle from alert to recovery.

---
