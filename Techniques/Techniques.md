## <ins>Valid Accounts</ins>  

**ID** : **`T1078`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0001` | **Initial Access** |
| 2. | `TA0003` | **Persistence** |
| 3. | `TA0004` | **Privilege Escalation** |
| 4. | `TA0005` | **Defence Evasion** |

Adversaries may obtain and abuse credentials of existing accounts.

Compromised credentials may be used to bypass access controls placed on various resources on systems within the network and may even be used for persistent access to remote systems and externally available services, such as VPNs, Outlook Web Access, network devices, and remote desktop.

Compromised credentials may also grant an adversary increased privilege to specific systems or access to restricted areas of the network.

Adversaries may choose not to use malware or tools in conjunction with the legitimate access those credentials provide to make it harder to detect their presence. 

---

## <ins>Replication Through Removable Media</ins>

**ID** : **`T1091`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0001`| **Initial Access** |
| 2. | `TA0008` | **Lateral Movement** |

Adversaries may move onto systems, possibly those on disconnected or air-gapped networks, by copying malware to removable media and taking advantage of Autorun features when the media is inserted into a system and executes.

In the case of Initial Access, this may occur through manual manipulation of the media, modification of systems used to initially format the media, or modification to the media's firmware itself.

In the case of Lateral Movement, this may occur through modification of executable files stored on removable media or by copying malware and renaming it to look like a legitimate file to trick users into executing it on a separate system. 

---

## <ins>External Remote Services</ins>

**ID** : **`T1133`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0001` | **Initial Access** |
| 2. | `TA0003` | **Persistence** |

Adversaries may leverage external-facing remote services to initially access and/or persist within a network.

- Remote services such as VPNs, Citrix, and other access mechanisms allow users to connect to internal enterprise network resources from external locations.

- There are often remote service gateways that manage connections and credential authentication for these services.

- Services such as Windows Remote Management and VNC can also be used externally.

--- 

## <ins>Drive-by Compromise</ins>

**ID** : **`T1189`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0001` | **Initial Access** |

Adversaries may gain access to a system through a user visiting a website over the normal course of browsing.

With this technique, the user's web browser is typically targeted for exploitation, but adversaries may also use compromised websites for non-exploitation behavior such as acquiring Application Access Token.

---

## <ins>Exploit Public Facing Application</ins>

**ID** : **`T1190`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | **`TA0001`** | **Initial Access** |

Adversaries may attempt to exploit a weakness in an Internet-facing host or system to initially access a network. The weakness in the system can be a software bug, a temporary glitch, or a misconfiguration.

---

<!-- ## <ins></ins>

**ID** : **`T11`**

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | | | -->


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
Access through trusted third party relationship abuses an existing connection that may not be protected or receives less scrutiny than standard mechanisms of gaining access to a network.
