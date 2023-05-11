## <ins>Windows Management Instrumentation</ins>  

**ID** : **`T1047`**

--- 

| S.No. | ID | Tactics |
| --- | --- | --- |
| 1. | `TA0002` | **Execution** |


| Platforms |
| --- |
| **`Windows`** |


**Supports Remote**:  **`Yes`** 

----

Adversaries may abuse Windows Management Instrumentation (WMI) to execute malicious commands and payloads.

`WMI is an administration feature that provides a uniform environment to access Windows system components.`

The WMI service enables both local and remote access, though the latter is facilitated by Remote Services such as **`Distributed Component Object Model`** (DCOM) and **`Windows Remote Management`** (WinRM).

An adversary can use WMI to interact with local and remote systems and use it as a means to execute various behaviors, such as gathering information for Discovery as well as remote Execution of files as part of [**Lateral Movement**](https://attack.mitre.org/tactics/TA0008/).