### TA0002

### Description

**The adversary is trying to run malicious code.**

- Execution consists of techniques that result in adversary-controlled code running on a local or remote system. 
- Techniques that run malicious code are often paired with techniques from all other tactics to achieve broader goals, like exploring a network or stealing data. 

- For example, an adversary might use a remote access tool to run a PowerShell script that does Remote System Discovery. 

---

### Techniques

| S.No. | ID | Techniques |
| --- | --- | --- |
| 1. | `T1047` | **Windows Management Instrumentation** |
| 2. | `T1053` | **Scheduled Task/Job** |
| 3. | `T1059` |  **Command And Scripting Interpreter** |
| 4. | `T1072` | **Software Deployment Tools** |
| 5. | `T1106` | **Native API** |
| 6. | `T1129` | **Shared Modules** |
| 7. | `T1203` | **Exploitation for Client Execution** |
| 8. | `T1204` | **User Execution** |
| 9. | `T1559` | **Inter-Process Communication** |
| 10. | `T1569` | **System Services** |
| 11. | `T1609` | **Container Administration Command** |
| 12. | `T1610` | **Deploy Container** |
| 13. | `T1648` | **Serverless Execution** |
| 14. | `T1651` | **Cloud Administration Command** |