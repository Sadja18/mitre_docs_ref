## <ins>Windows Management Instrumentation</ins>  

**ID** : **`T1047`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0002` | **Execution** |

Adversaries may abuse Windows Management Instrumentation (WMI) to execute malicious commands and payloads.

---

## <ins>Scheduled Task/Job</ins>  

**ID** : **`T1053`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0002` | **Execution** |
| 2. | `TA0003` | **Persistence** |
| 3. | `TA0004` | **Privilege Escalation** |


Adversaries may abuse task scheduling functionality to facilitate initial or recurring execution of malicious code. 

---

## <ins>Command And Scripting Interpreter</ins>  

**ID** : **`T1059`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0002` | **Execution** |

Adversaries may abuse command and script interpreters to execute commands, scripts, or binaries. 

---

## <ins>Valid Accounts</ins>  

**ID** : **`T1078`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0001` | **Initial Access** |
| 2. | `TA0003` | **Persistence** |
| 3. | `TA0004` | **Privilege Escalation** |
| 4. | `TA0005` | **Defence Evasion** |

Adversaries may obtain and abuse credentials of existing accounts.

---

## <ins>Replication Through Removable Media</ins>

**ID** : **`T1091`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0001`| **Initial Access** |
| 2. | `TA0008` | **Lateral Movement** |

Adversaries may move onto systems, possibly those on disconnected or air-gapped networks, by copying malware to removable media and taking advantage of Autorun features when the media is inserted into a system and executes. 

---

## <ins>External Remote Services</ins>

**ID** : **`T1133`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0001` | **Initial Access** |
| 2. | `TA0003` | **Persistence** |

Adversaries may leverage external-facing remote services to initially access and/or persist within a network.

--- 

## <ins>Drive-by Compromise</ins>

**ID** : **`T1189`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0001` | **Initial Access** |

Adversaries may gain access to a system through a user visiting a website over the normal course of browsing.

---

## <ins>Exploit Public Facing Application</ins>

**ID** : **`T1190`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | **`TA0001`** | **Initial Access** |

Adversaries may attempt to exploit a weakness in an Internet-facing host or system to initially access a network. The weakness in the system can be a software bug, a temporary glitch, or a misconfiguration.

---


## <ins>Supply Chain Compromise</ins>

**ID** : **`T1195`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | **`TA0001`** | **Initial Access** |

Adversaries may manipulate products or product delivery mechanisms prior to receipt by a final consumer for the purpose of data or system compromise.

---

## <ins>Trusted Relationship</ins>

**ID** : **`T1199`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0001` | **Initial Access** |

Adversaries may breach or otherwise leverage organizations who have access to intended victims. 
