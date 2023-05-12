### TA0004

### Description

**The adversary is trying to gain higher-level permissions.**

- Privilege Escalation consists of techniques that adversaries use to gain higher-level permissions on a system or network. 

- Adversaries can often enter and explore a network with unprivileged access but require elevated permissions to follow through on their objectives. 
- Common approaches are to take advantage of system weaknesses, misconfigurations, and vulnerabilities. 

Examples of elevated access include:

- SYSTEM/root level
- local administrator
- user account with admin-like access
- user accounts with access to specific system or perform specific function

These techniques often overlap with Persistence techniques, as OS features that let an adversary persist can execute in an elevated context. 

---

### Techniques

| S.No. | ID | Techniques |
| --- | --- | --- |
| 1. | `T1037` | **Boot or Logon Autostart Execution** |
| 2. | `T1053` | **Scheduled Task/Job** |
| 3. | `T1055` | **Process Injection** |
| 4. | `T1068` | **Exploitation for Privilege Escalation** |
| 5. | `T1078` | **Valid Accounts** |
| 6. | `T1134` | **Access Token Manipulation** |
| 7. | `T1484` | **Group Policy Modification** |
| 8. | `T1543` | **Create or Modify System Process** |
| 9. | `T1546` | **Event Triggered Execution** |
| 10. | `T1547` | **Registry Run Keys / Start Folder** |
| 11. | `T1548` | **Abuse Elevation Control Mechanism** |
| 12. | `T1574` | **Hijack Execution Flow** |
| 13. | `T1611` | **No-Op** |