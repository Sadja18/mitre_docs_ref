## Replication Through Removable Media 

**ID** : **`T1091`**

----

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0001`| **Initial Access** |
| 2. | `TA0008` | **Lateral Movement** |

| Platforms |
| --- |
| **`Windows`** |

| System Requirements |
| --- |
| Removable media allowed, |
| Autorun enabled or vulnerability present that allows for code execution | 

---

Adversaries may move onto systems, possibly those on disconnected or air-gapped networks, by copying malware to removable media and taking advantage of Autorun features when the media is inserted into a system and executes.

In the case of Initial Access, this may occur through manual manipulation of the media, modification of systems used to initially format the media, or modification to the media's firmware itself.

In the case of Lateral Movement, this may occur through modification of executable files stored on removable media or by copying malware and renaming it to look like a legitimate file to trick users into executing it on a separate system. 
